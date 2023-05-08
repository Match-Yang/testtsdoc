


# getCallkitProviderDidResetEventStream method








Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)> getCallkitProviderDidResetEventStream
()

_<span class="feature">inherited</span>_



<p>Called when the provider has been reset. Delegates must respond to this callback by cleaning up all internal call state (disconnecting communication channels, releasing network resources, etc.). This callback can be treated as a request to end all calls without the need to respond to any actions</p>



## Implementation

```dart
Stream<ZegoSignalingPluginCallKitVoidEvent>
    getCallkitProviderDidResetEventStream() {
  return ZegoPluginAdapter()
      .signalingPlugin!
      .getCallkitProviderDidResetEventStream();
}
```







