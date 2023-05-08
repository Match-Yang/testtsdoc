


# updateScreenCaptureConfig method








Future&lt;void> updateScreenCaptureConfig
([ZegoScreenCaptureConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureConfig-class.md) config)





<p>Update screen capture parameter configuration.</p>
<p>Available since: 3.1.0
Description: Update screen capture parameter configuration.
When to call: After calling <code>startScreenCapture</code> to start capturing.
Restrictions: Only support in iOS. Only available on iOS 12.0 or newer</p>
<ul>
<li><code>config</code> Screen capture parameter configuration.</li>
</ul>



## Implementation

```dart
Future<void> updateScreenCaptureConfig(ZegoScreenCaptureConfig config);
```







