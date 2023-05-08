


# updateUserName method








Future&lt;[ZIMUserNameUpdatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMUserNameUpdatedResult-class.md)> updateUserName
(String userName)





<p>Available since: 2.2.0 and above.</p>
<p>Description: Through this interface, you can update your user name.</p>
<p>When to call /Trigger: It is available only after calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> to create the instance and then calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/login.md">login</a> to login.</p>
<p><code>userName</code> the user name you want to update.</p>



## Implementation

```dart
Future<ZIMUserNameUpdatedResult> updateUserName(String userName);
```







