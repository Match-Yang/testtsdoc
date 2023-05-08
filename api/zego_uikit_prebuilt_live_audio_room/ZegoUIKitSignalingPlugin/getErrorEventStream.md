


# getErrorEventStream method







- @override

Stream&lt;[ZegoSignalingPluginErrorEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginErrorEvent-class.md)> getErrorEventStream
()

_<span class="feature">override</span>_



<p>get error event stream</p>



## Implementation

```dart
@override
Stream<ZegoSignalingPluginErrorEvent> getErrorEventStream() {
  return ZegoSignalingPluginCore().eventCenter.errorEvent.stream;
}
```







