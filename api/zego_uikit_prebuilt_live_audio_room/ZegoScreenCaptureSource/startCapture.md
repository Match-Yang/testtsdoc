


# startCapture method








Future&lt;void> startCapture
({[ZegoScreenCaptureConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureConfig-class.md)? config, bool? inApp})





<p>Start screen capture.</p>
<p>Available since: 3.1.0
Description: Start screen capture.
When to call: It can be called after the engine by <code>createScreenCaptureSource</code> has been initialized.</p>
<ul>
<li><code>config</code> Screen capture parameter configuration, only available on the iOS platform.</li>
<li><code>inApp</code> in-app capture only, only available on the iOS platform.</li>
</ul>



## Implementation

```dart
Future<void> startCapture({ZegoScreenCaptureConfig? config, bool? inApp});
```







