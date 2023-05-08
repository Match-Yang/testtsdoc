


# onExceptionOccurred property







(void Function([ZegoScreenCaptureSource](../../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureSource-class.md) source, [ZegoScreenCaptureSourceExceptionType](../../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureSourceExceptionType.md) exceptionType)?) onExceptionOccurred
  
_<span class="feature">read / write</span>_



<p>The callback triggered when a screen capture source exception occurred</p>
<p>Available since: 3.1.0
Description: The callback triggered when a screen capture source exception occurred.
Trigger: This callback is triggered when an exception occurs after the screen start capture.
Caution: The callback does not actually take effect until call <code>setEventHandler</code> to set.</p>
<ul>
<li><code>source</code> Callback screen capture source object.</li>
<li><code>exceptionType</code> Capture source exception type.</li>
</ul>



## Implementation

```dart
static void Function(ZegoScreenCaptureSource source,
    ZegoScreenCaptureSourceExceptionType exceptionType)? onExceptionOccurred;
```







