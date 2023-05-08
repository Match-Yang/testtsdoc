


# updateGroupName method








Future&lt;[ZIMGroupNameUpdatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupNameUpdatedResult-class.md)> updateGroupName
(String groupName, String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a group is created, users can call this method to change the group name.</p>
<p>Use cases: After creating a group, you need to change the group name.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: Group members and group owners can change the group name. The maximum length of the name is 100 bytes.</p>
<p>Related APIs: Through the callback <code>ZIMGroupNameUpdatedResult</code> can get the result of the change of name, through <code>ZIMEventHandler.onGroupNoticeUpdated</code> can get update group name information.</p>
<p><code>groupName</code> The updated group name.
<code>groupID</code> The group ID whose group name will be updated.</p>



## Implementation

```dart
Future<ZIMGroupNameUpdatedResult> updateGroupName(
    String groupName, String groupID);
```







