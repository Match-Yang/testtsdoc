


# getCallkitProviderDidBeginEventStream method








Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)> getCallkitProviderDidBeginEventStream
()

_<span class="feature">inherited</span>_



<p>Called when the provider has been fully created and is ready to send actions and receive updates</p>



## Implementation

```dart
Stream<ZegoSignalingPluginCallKitVoidEvent>
    getCallkitProviderDidBeginEventStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getCallkitProviderDidBeginEventStream();
}
```







