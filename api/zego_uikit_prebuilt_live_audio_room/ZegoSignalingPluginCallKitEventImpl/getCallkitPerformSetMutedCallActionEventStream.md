


# getCallkitPerformSetMutedCallActionEventStream method







- @override

Stream&lt;[ZegoSignalingPluginCallKitSetMutedCallActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitSetMutedCallActionEvent-class.md)> getCallkitPerformSetMutedCallActionEventStream
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Stream<ZegoSignalingPluginCallKitSetMutedCallActionEvent>
    getCallkitPerformSetMutedCallActionEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .callkitPerformSetMutedCallActionEvent
      .stream;
}
```







