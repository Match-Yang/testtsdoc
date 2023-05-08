


# zego_uikit_prebuilt_live_audio_room - Dart API docs


<hr>
<h1 id="overview">Overview</h1>
<hr>
<p><strong>Live Audio Room Kit</strong> is a prebuilt component that helps you to build full-featured live audio rooms into your apps easier.</p>
<p>And it includes the business logic along with the UI, enabling you to customize your live audio apps faster with more flexibility.</p>
<p><img src="https://storage.zego.im/sdk-doc/Pics/ZegoUIKit/Flutter/audio_room/final_sublist.gif" alt="overview.gif"></p>
<h2 id="when-do-you-need-the-live-audio-room-kit">When do you need the Live Audio Room Kit</h2>
<ul>
<li>
<p>When you want to build live audio rooms easier and faster, it allows you:</p>
<blockquote>
<p>Build or prototype live audio apps ASAP</p>
</blockquote>
<blockquote>
<p>Finish the integration in the shortest possible time</p>
</blockquote>
</li>
<li>
<p>When you want to customize UI and features as needed, it allows you:</p>
<blockquote>
<p>Customize features based on actual business needs</p>
</blockquote>
<blockquote>
<p>Spend less time wasted developing basic features</p>
</blockquote>
<blockquote>
<p>Add or remove features accordingly</p>
</blockquote>
</li>
</ul>
<p>To build a live audio app from scratch, you may check our <a href="https://docs.zegocloud.com/article/13257">Voice Call</a>.</p>
<h2 id="embedded-features">Embedded features</h2>
<ul>
<li>Ready-to-use Live Audio Room</li>
<li>Remove speakers</li>
<li>Speaker seats changing</li>
<li>Customizable seat layout</li>
<li>Extendable menu bar</li>
<li>Device management</li>
<li>Customizable UI style</li>
<li>Real-time interactive text chat</li>
</ul>
<h2 id="recommended-resources">Recommended resources</h2>
<ul>
<li>I want to <a href="https://docs.zegocloud.com/article/15079">get started</a> to implement a live audio room swiftly</li>
<li>To <a href="https://docs.zegocloud.com/article/15083">configure prebuilt UI</a> for a custom experience</li>
<li>I want to get the <a href="https://github.com/ZEGOCLOUD/zego_uikit_prebuilt_live_audio_room_example_flutter">Sample Code</a></li>
<li>To make a fully customized Live Audio app, you may try <a href="https://docs.zegocloud.com/article/13257">this SDK</a></li>
</ul>
<hr>
<h1 id="quick-start">Quick start</h1>
<hr>
<h2 id="prerequisites">Prerequisites</h2>
<ul>
<li>Go to <a href="https://console.zegocloud.com">ZEGOCLOUD Admin Console</a>, and do the following:
<ul>
<li>Create a project, get the <strong>AppID</strong> and <strong>AppSign</strong>.</li>
<li>Activate the <strong>In-app Chat</strong> service (as shown in the following figure).
<img src="https://storage.zego.im/sdk-doc/Pics/InappChat/ActivateZIMinConsole2.png" alt="ActivateZIMinConsole2.png"></li>
</ul>
</li>
</ul>
<h2 id="integrate-the-sdk">Integrate the SDK</h2>
<h3 id="add-zegouikitprebuiltliveaudioroom-as-dependencies">Add ZegoUIKitPrebuiltLiveAudioRoom as dependencies</h3>
<p>Run the following code in your project's root directory:</p>
<pre class="language-dart"><code class="language-dart">flutter pub add zego_uikit_prebuilt_live_audio_room
</code></pre>
<h3 id="import-the-sdk">Import the SDK</h3>
<p>Now in your Dart code, import the Live Audio Room Kit SDK.</p>
<pre class="language-dart"><code class="language-dart">import 'package:zego_uikit_prebuilt_live_audio_room/zego_uikit_prebuilt_live_audio_room.dart';
</code></pre>
<h2 id="using-the-live-audio-room-kit">Using the Live Audio Room Kit</h2>
<ul>
<li>Specify the <code>userID</code> and <code>userName</code> for connecting the Live Audio Room Kit service.</li>
<li><code>roomID</code> represents the live audio room you want to create or join.</li>
</ul>
<div class="mk-hint">
<ul>
<li><code>userID</code>, <code>userName</code>, and <code>roomID</code> can only contain numbers, letters, and underlines (_).</li>
<li>Using the same <code>roomID</code> will enter the same live audio room.</li>
</ul>
</div>
<div class="mk-warning">
<p>With the same <code>roomID</code>, only one user can enter the live audio room as host. Other users need to enter the live audio room as the audience.</p>
</div>
<pre class="language-dart"><code class="language-dart">class LivePage extends StatelessWidget {
  final String roomID;
  final bool isHost;

  const LivePage({Key? key, required this.roomID, this.isHost = false}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return SafeArea(
      child: ZegoUIKitPrebuiltLiveAudioRoom(
        appID: yourAppID, // Fill in the appID that you get from ZEGOCLOUD Admin Console.
        appSign: yourAppSign, // Fill in the appSign that you get from ZEGOCLOUD Admin Console.
        userID: 'user_id',
        userName: 'user_name',
        roomID: roomID,
        config: isHost
            ? ZegoUIKitPrebuiltLiveAudioRoomConfig.host()
            : ZegoUIKitPrebuiltLiveAudioRoomConfig.audience(),
      ),
    );
  }
}
</code></pre>
<p>Then, you can create a live audio room. And the audience can join the live audio room by entering the <code>roomID</code>.</p>
<h2 id="config-your-project">Config your project</h2>
<ul>
<li>Android:</li>
</ul>
<ol>
<li>
<p>If your project is created with Flutter 2.x.x, you will need to open the <code>your_project/android/app/build.gradle</code> file, and modify the <code>compileSdkVersion</code> to <strong>33</strong>.</p>
<p><img src="https://storage.zego.im/sdk-doc/Pics/ZegoUIKit/Flutter/compile_sdk_version.png" alt="compileSdkVersion"></p>
</li>
<li>
<p>Add app permission.
Open the file <code>your_project/app/src/main/AndroidManifest.xml</code>, and add the following:</p>
<pre class="language-xml"><code class="language-xml">&lt;uses-permission android:name="android.permission.ACCESS_WIFI_STATE" /&gt;
&lt;uses-permission android:name="android.permission.RECORD_AUDIO" /&gt;
&lt;uses-permission android:name="android.permission.INTERNET" /&gt;
&lt;uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" /&gt;
&lt;uses-permission android:name="android.permission.CAMERA" /&gt;
&lt;uses-permission android:name="android.permission.BLUETOOTH" /&gt;
&lt;uses-permission android:name="android.permission.MODIFY_AUDIO_SETTINGS" /&gt;
&lt;uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" /&gt;
&lt;uses-permission android:name="android.permission.READ_PHONE_STATE" /&gt;
&lt;uses-permission android:name="android.permission.WAKE_LOCK" /&gt;
</code></pre>
 <img src="https://storage.zego.im/sdk-doc/Pics/ZegoUIKit/Flutter/live/permission_android.png" width="800">
</li>
<li>
<p>Prevent code obfuscation.</p>
</li>
</ol>
<p>To prevent obfuscation of the SDK public class names, do the following:</p>
<p>a. In your project's <code>your_project &gt; android &gt; app</code> folder, create a <code>proguard-rules.pro</code> file with the following content as shown below:</p>
<pre style="background-color: #011627; border-radius: 8px; padding: 25px; color: white" class="language-dart"><div>
-keep class **.zego.** { *; }
</div></pre>
<p>b. Add the following config code to the <code>release</code> part of the <code>your_project/android/app/build.gradle</code> file.</p>
<pre style="background-color: #011627; border-radius: 8px; padding: 25px; color: white" class="language-dart"><div>
proguardFiles getDefaultProguardFile('proguard-android.txt'), 'proguard-rules.pro'
</div></pre>
<p><img src="https://storage.zego.im/sdk-doc/Pics/ZegoUIKit/Flutter/android_class_confusion.png" alt="android_class_confusion.png"></p>
<ul>
<li>iOS:</li>
</ul>
<ol>
<li>Add app permissions.</li>
</ol>
<p>a. open the <code>your_project/ios/Podfile</code> file, and add the following to the <code>post_install do |installer|</code> part:</p>
<pre class="language-plist"><code class="language-plist"># Start of the permission_handler configuration
target.build_configurations.each do |config|
  config.build_settings['GCC_PREPROCESSOR_DEFINITIONS'] ||= [
    '$(inherited)',
    'PERMISSION_CAMERA=1',
    'PERMISSION_MICROPHONE=1',
  ]
end
# End of the permission_handler configuration
</code></pre>
<img src="https://storage.zego.im/sdk-doc/Pics/ZegoUIKit/Flutter/live/permission_podfile.png" width="800">
<p>b. open the <code>your_project/ios/Runner/Info.plist</code> file, and add the following to the <code>dict</code> part:</p>
<pre class="language-plist"><code class="language-plist">    &lt;key&gt;NSCameraUsageDescription&lt;/key&gt;
    &lt;string&gt;We require camera access to connect to a live&lt;/string&gt;
    &lt;key&gt;NSMicrophoneUsageDescription&lt;/key&gt;
    &lt;string&gt;We require microphone access to connect to a live&lt;/string&gt;
</code></pre>
<img src="https://storage.zego.im/sdk-doc/Pics/ZegoUIKit/Flutter/live/permission_ios.png" width="800">
<ol start="2">
<li>Disable the Bitcode.</li>
</ol>
<p>a. Open the <code>your_project &gt; iOS &gt; Runner.xcworkspace</code> file.</p>
<p>b. Select your target project, and follow the notes on the following two images to disable the Bitcode respectively.</p>
<img src="https://storage.zego.im/sdk-doc/Pics/ZegoUIKit/Flutter/bitcode_1.png" width="800">
<img src="https://storage.zego.im/sdk-doc/Pics/ZegoUIKit/Flutter/bitcode_2.png" width="800">
<h2 id="run--test">Run &amp; Test</h2>
<p>Now you can simply click the <strong>Run</strong> or <strong>Debug</strong> button to run and test your App on the device.
<img src="https://storage.zego.im/sdk-doc/Pics/ZegoUIKit/Flutter/run_flutter_project.jpg" alt="run_flutter_project.jpg"></p>
<h2 id="related-guide">Related guide</h2>
<p><a href="https://docs.zegocloud.com/article/15083">Custom prebuilt UI</a></p>
<h2 id="resources">Resources</h2>
<p>Click to get the complete <a href="https://github.com/ZEGOCLOUD/zego_uikit_prebuilt_live_audio_room_example_flutter">sample code</a>.</p>


## Libraries

##### [zego_uikit_prebuilt_live_audio_room](zego_uikit_prebuilt_live_audio_room/zego_uikit_prebuilt_live_audio_room-library.md)









