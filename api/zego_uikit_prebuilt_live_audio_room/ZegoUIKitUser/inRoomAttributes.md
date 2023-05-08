


# inRoomAttributes property









ValueNotifier&lt;ZegoUIKitUserAttributes> inRoomAttributes
  







## Implementation

```dart
ValueNotifier<ZegoUIKitUserAttributes> get inRoomAttributes {
  return ZegoUIKitCore.shared.coreData.getUser(id).inRoomAttributes;
}
```








