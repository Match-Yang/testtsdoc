


# getInRoomUserAttributesNotifier method








ValueNotifier&lt;ZegoUIKitUserAttributes> getInRoomUserAttributesNotifier
(String userID)





<p>get notifier of in-room user attributes</p>



## Implementation

```dart
ValueNotifier<ZegoUIKitUserAttributes> getInRoomUserAttributesNotifier(
    String userID) {
  return ZegoUIKitCore.shared.coreData.getUser(userID).inRoomAttributes;
}
```







