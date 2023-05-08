


# getCallkitProviderDidBeginEventStream method







- @override

Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)> getCallkitProviderDidBeginEventStream
()

_<span class="feature">override</span>_



<p>Called when the provider has been fully created and is ready to send actions and receive updates</p>



## Implementation

```dart
@override
Stream<ZegoSignalingPluginCallKitVoidEvent>
    getCallkitProviderDidBeginEventStream() {
  return ZegoSignalingPluginCore()
      .eventCenter
      .callkitProviderDidBeginEvent
      .stream;
}
```







