


# activeAudioByCallKit method








Future&lt;void> activeAudioByCallKit
()





<p>Call this function when you <code>didReceiveIncomingPush</code> to active audio in callkit mode</p>



## Implementation

```dart
Future<void> activeAudioByCallKit() async {
  return ZegoSignalingPluginCore.shared.activeAudioByCallKit();
}
```







