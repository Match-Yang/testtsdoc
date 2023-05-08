


# inviteAudienceToTakeSeat method








Future&lt;bool> inviteAudienceToTakeSeat
(String userID)





<p>Host invite the audience with id <code>userID</code> to take seat</p>



## Implementation

```dart
Future<bool> inviteAudienceToTakeSeat(String userID) async {
  return await _connectManager?.inviteAudienceConnect(
        ZegoUIKit().getUser(userID) ?? ZegoUIKitUser.empty(),
      ) ??
      false;
}
```







