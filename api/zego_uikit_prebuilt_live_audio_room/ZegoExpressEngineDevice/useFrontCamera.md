


# useFrontCamera method








Future&lt;void> useFrontCamera
(bool enable, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Switches to the front or the rear camera (for the specified channel).</p>
<p>Available since: 1.1.0
Description: This function is used to control the use of the front camera or the rear camera (only supported by Android and iOS).
Default value: The default is <code>true</code> which means the front camera is used.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Caution: When the custom video capture function <code>enableCustomVideoCapture</code> is turned on, since the developer has taken over the video data capture, the SDK is no longer responsible for the video data capture, and this function is no longer valid.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>enable</code> Whether to use the front camera, <code>true</code>: use the front camera, <code>false</code>: use the the rear camera.</li>
<li><code>channel</code> Publishing stream channel</li>
</ul>



## Implementation

```dart
Future<void> useFrontCamera(bool enable,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .useFrontCamera(enable, channel: channel);
}
```







