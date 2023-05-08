


# getTokenWillExpireEventStream method







- @override

Stream&lt;[ZegoSignalingPluginTokenWillExpireEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginTokenWillExpireEvent-class.md)> getTokenWillExpireEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginTokenWillExpireEvent>
    getTokenWillExpireEventStream() {
  return ZegoSignalingPluginCore().eventCenter.tokenWillExpireEvent.stream;
}
```







