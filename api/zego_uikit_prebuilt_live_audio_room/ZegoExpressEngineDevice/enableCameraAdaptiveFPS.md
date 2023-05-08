


# enableCameraAdaptiveFPS method








Future&lt;void> enableCameraAdaptiveFPS
(bool enable, int minFPS, int maxFPS, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)





<p>Enable camera adaptive frame rate.</p>
<p>Available since: 2.20.0
Description: After enabling, the SDK matches the capture frame rate range supported by the camera according to the set frame rate range, and dynamically adjusts the capture frame rate of the camera according to the ambient brightness within this range to improve the screen brightness when the set frame rate is too high.
Use cases: The frame rate set by the user on the streaming end is too high, and the ambient lighting is low, so the subject cannot be displayed or recognized normally. For example, live broadcast scenes with high exposure requirements.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, before the camera starts.
Caution: Takes When calling <code>setVideoConfig</code> to set the frame rate lower than the expected minimum frame rate, the frame rate value set by <code>setVideoConfig</code> will be used. Due to the different hardware and algorithm strategies of different mobile phone manufacturers, the effect of this interface is different on different models or on the front and rear cameras of the same model.
Related APIs: Through <code>setVideoConfig</code>, you can set the camera capture frame rate and the encoder encoding frame rate.</p>
<ul>
<li><code>enable</code> Whether to enable camera adaptive frame rate. true means on, false means off.Off by default.</li>
<li><code>minFPS</code> Desired minimum frame rate, 15 recommended. Unit: fps.</li>
<li><code>maxFPS</code> Desired minimum frame rate, 25 recommended. Unit: fps.</li>
<li><code>channel</code> Publishing stream channel.</li>
</ul>



## Implementation

```dart
Future<void> enableCameraAdaptiveFPS(
    bool enable, int minFPS, int maxFPS, ZegoPublishChannel channel) async {
  return await ZegoExpressImpl.instance
      .enableCameraAdaptiveFPS(enable, minFPS, maxFPS, channel);
}
```







