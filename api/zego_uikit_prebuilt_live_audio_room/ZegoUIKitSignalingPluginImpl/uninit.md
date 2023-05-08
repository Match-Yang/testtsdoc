


# uninit method








Future&lt;void> uninit
()





<p>uninit</p>



## Implementation

```dart
Future<void> uninit() async {
  uninitUserInRoomAttributes();

  return ZegoSignalingPluginCore.shared.uninit();
}
```







