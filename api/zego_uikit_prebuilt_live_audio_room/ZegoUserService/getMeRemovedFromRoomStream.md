


# getMeRemovedFromRoomStream method








Stream&lt;String> getMeRemovedFromRoomStream
()





<p>get kicked out notifier</p>



## Implementation

```dart
Stream<String> getMeRemovedFromRoomStream() {
  return ZegoUIKitCore.shared.coreData.meRemovedFromRoomStreamCtrl.stream;
}
```







