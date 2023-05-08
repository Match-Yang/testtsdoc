


# destroyScreenCaptureSource method








Future&lt;void> destroyScreenCaptureSource
([ZegoScreenCaptureSource](../../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureSource-class.md) source)





<p>Destroy the screen capture source instance</p>
<p>Available: since 3.1.0
Description: Destroy the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureSource-class.md">ZegoScreenCaptureSource</a> instance object.
Use cases: When you no longer need to use the screen capture function, you can use this function to destroy the instance object created by the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineScreenCapture/createScreenCaptureSource.md">createScreenCaptureSource</a> function
When to call: When you need to the screen capture source object needs to be destroyed
Restrictions: After destroy the instance, you need to release the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureSource-class.md">ZegoScreenCaptureSource</a> instance object you hold by yourself, and don’t call the function of this instance object after the destruction.</p>
<ul>
<li><code>source</code> The screen capture source instance to be destroyed.</li>
</ul>



## Implementation

```dart
Future<void> destroyScreenCaptureSource(
    ZegoScreenCaptureSource source) async {
  return await ZegoExpressImpl.instance.destroyScreenCaptureSource(source);
}
```







