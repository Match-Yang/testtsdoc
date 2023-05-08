


# queryUsersInfo method








Future&lt;[ZIMUsersInfoQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult-class.md)> queryUsersInfo
(List&lt;String> userIDs, [ZIMUserInfoQueryConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMUserInfoQueryConfig-class.md) config)





<p>Available since: 2.1.5 and above.</p>
<p>Description: Through this interface, you can query and obtain the corresponding UserInfo by userID.</p>
<p>When to call /Trigger: It is available only after calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> to create the instance and then calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/login.md">login</a> to login.</p>
<p><code>userIDs</code> userID list.
<code>config</code> query config.</p>



## Implementation

```dart
Future<ZIMUsersInfoQueriedResult> queryUsersInfo(
    List<String> userIDs, ZIMUserInfoQueryConfig config);
```







