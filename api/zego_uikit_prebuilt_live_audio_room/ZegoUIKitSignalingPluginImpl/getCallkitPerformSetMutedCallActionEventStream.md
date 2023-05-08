


# getCallkitPerformSetMutedCallActionEventStream method








Stream&lt;[ZegoSignalingPluginCallKitSetMutedCallActionEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitSetMutedCallActionEvent-class.md)> getCallkitPerformSetMutedCallActionEventStream
()

_<span class="feature">inherited</span>_






## Implementation

```dart
Stream<ZegoSignalingPluginCallKitSetMutedCallActionEvent>
    getCallkitPerformSetMutedCallActionEventStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getCallkitPerformSetMutedCallActionEventStream();
}
```







