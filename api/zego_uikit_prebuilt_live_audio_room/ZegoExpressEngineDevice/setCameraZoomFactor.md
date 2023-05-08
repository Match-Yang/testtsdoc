


# setCameraZoomFactor method








Future&lt;void> setCameraZoomFactor
(double factor, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Set the zoom factor of the camera. Every time the camera is restarted, the camera zoom factor will return to the initial value (1.0).</p>
<p>Available since: 1.20.0
Description: Set the camera zoom factor. Every time the camera is restarted, the camera zoom factor will be restored to its initial value.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: The settings will not take effect until the camera is started.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>factor</code> The zoom factor of the camera, the minimum value is 1.0, and the maximum value is the return value of <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/getCameraMaxZoomFactor.md">getCameraMaxZoomFactor</a>.</li>
<li><code>channel</code> Publishing stream channel</li>
</ul>



## Implementation

```dart
Future<void> setCameraZoomFactor(double factor,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setCameraZoomFactor(factor, channel: channel);
}
```







