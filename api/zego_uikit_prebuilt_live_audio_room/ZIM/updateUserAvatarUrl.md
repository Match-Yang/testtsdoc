


# updateUserAvatarUrl method








Future&lt;[ZIMUserAvatarUrlUpdatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMUserAvatarUrlUpdatedResult-class.md)> updateUserAvatarUrl
(String userAvatarUrl)





<p>Available since: 2.3.0 and above.</p>
<p>Description: Through this interface, you can update your user avatar url.</p>
<p>When to call /Trigger: It is available only after calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> to create the instance and then calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/login.md">login</a> to login.</p>
<p><code>userAvatarUrl</code> the user avatar url you want to update.</p>



## Implementation

```dart
Future<ZIMUserAvatarUrlUpdatedResult> updateUserAvatarUrl(
    String userAvatarUrl);
```







