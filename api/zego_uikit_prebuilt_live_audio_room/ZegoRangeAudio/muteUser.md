


# muteUser method








Future&lt;void> muteUser
(String userID, bool mute)





<p>Whether can receive the audio data of the specified user.</p>
<p>Available since: 2.16.0
Description: In the process of real-time audio and video interaction, local users can use this function to control whether to receive audio data from designated remote users when pulling streams as needed. When the developer does not receive the audio receipt, the hardware and network overhead can be reduced.
Use cases: When developers need to quickly close and restore remote audio, they can call this function to enhance the interactive experience.
Default value: The default is <code>false</code>, which means to receive audio data from all users.
When to call: After initializing the range audio <code>createRangeAudio</code>.
Caution: This function is valid only when the <code>muteAllPlayStreamAudio</code> function is set to <code>false</code>.
Related APIs: You can call the <code>muteAllPlayStreamAudio</code> function to control whether to receive all audio data. 1. When the <code>muteAllPlayStreamAudio(true)</code> function is called, it takes effect globally, that is, local users will be prohibited from receiving audio data from all remote users. At this time, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/muteUser.md">muteUser</a> function will not take effect regardless of whether the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/muteUser.md">muteUser</a> function is called before or after <code>muteAllPlayStreamAudio</code>. 2. When the <code>muteAllPlayStreamAudio(false)</code> function is called, the local user can receive the audio data of all remote users. At this time, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/muteUser.md">muteUser</a> function can be used to control whether to receive the audio data of the specified user. Calling the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/muteUser.md">muteUser(userID, true)</a> function allows the local user to receive audio data other than the <code>userID</code>; calling the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/muteUser.md">muteUser(userID, false)</a> function allows the local user to receive the audio data of the <code>userID</code>.</p>
<ul>
<li><code>userID</code> User ID.</li>
<li><code>mute</code> Whether it can receive the audio data of the specified remote user, "true" means prohibition, "false" means receiving, the default value is "false".</li>
</ul>



## Implementation

```dart
Future<void> muteUser(String userID, bool mute);
```







