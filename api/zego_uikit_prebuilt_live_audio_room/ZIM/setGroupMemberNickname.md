


# setGroupMemberNickname method








Future&lt;[ZIMGroupMemberNicknameUpdatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberNicknameUpdatedResult-class.md)> setGroupMemberNickname
(String nickname, String forUserID, String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a group is created, you can use this method to set nicknames for group members.</p>
<p>Use cases: Nicknames need to be set for group members.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: Available after login, unavailable after logout. The owner of a group can change his or her own nickname, while the members can change only their own nickname.</p>
<p>Caution: A group name can contain a maximum of 100 characters.</p>
<p><code>nickname</code>  Set member nickname.
<code>forUserID</code> User ID for which group nickname is set.
<code>groupID</code> The group ID of the group member's nickname is set.</p>



## Implementation

```dart
Future<ZIMGroupMemberNicknameUpdatedResult> setGroupMemberNickname(
    String nickname, String forUserID, String groupID);
```







