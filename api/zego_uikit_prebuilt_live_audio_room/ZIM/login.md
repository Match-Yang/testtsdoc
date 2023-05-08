


# login method








Future&lt;void> login
([ZIMUserInfo](../../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo-class.md) userInfo, [String? token])





<p>Login, you must log in before using all functions.
<code>userInfo</code> Unique ID used to identify the user. Note that the userID must be unique under the same appID, otherwise mutual kicks out will occur.
<code>token</code> The token issued by the developer's business server, used to ensure security. The generation rules are detailed in ZEGO document website.</p>



## Implementation

```dart
Future<void> login(ZIMUserInfo userInfo, [String? token]);
```







