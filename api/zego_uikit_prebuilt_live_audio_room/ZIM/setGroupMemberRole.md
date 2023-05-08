


# setGroupMemberRole method








Future&lt;[ZIMGroupMemberRoleUpdatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberRoleUpdatedResult-class.md)> setGroupMemberRole
(int role, String forUserID, String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a group is created, you can use this method to set the roles of group members.</p>
<p>Use cases: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>When to call /Trigger: If the primary role of a group is 1 and the default role of other members is 3, you can invoke this interface to change the role.</p>
<p>Caution: Non-group master unavailable.</p>
<p><code>role</code> Set of group roles.
<code>forUserID</code> User ID for which group role is set.
<code>groupID</code> The group ID of the group role to be set.</p>



## Implementation

```dart
Future<ZIMGroupMemberRoleUpdatedResult> setGroupMemberRole(
    int role, String forUserID, String groupID);
```







