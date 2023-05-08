


# enableCamera method








Future&lt;void> enableCamera
(bool enable, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Turns on/off the camera (for the specified channel).</p>
<p>Available since: 1.1.0
Description: This function is used to control whether to start the capture of the camera. After the camera is turned off, the video capture will not be performed. At this time, there will be no video data for local preview and push streaming.
Default value: The default is <code>true</code> which means the camera is turned on.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Caution: In the case of using the custom video capture function <code>enableCustomVideoCapture</code>, since the developer has taken over the video data capture, the SDK is no longer responsible for the video data capture, but this function still affects whether to encode or not. Therefore, when developers use custom video capture, please ensure that the value of this function is <code>true</code>.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>enable</code> Whether to turn on the camera, <code>true</code>: turn on camera, <code>false</code>: turn off camera</li>
<li><code>channel</code> Publishing stream channel</li>
</ul>



## Implementation

```dart
Future<void> enableCamera(bool enable, {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .enableCamera(enable, channel: channel);
}
```







