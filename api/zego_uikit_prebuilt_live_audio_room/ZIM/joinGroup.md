


# joinGroup method








Future&lt;[ZIMGroupJoinedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupJoinedResult-class.md)> joinGroup
(String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a group is created, other users can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/joinGroup.md">joinGroup</a> to join the group.</p>
<p>Use cases: This interface is used to join a group in a chat scenario.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Caution: Available after login, unavailable after logout. If you have joined a group, the join succeeds. A group is limited to 500 people and fails to join when it is full.</p>
<p>Related callbacks: To get the result of joining the room, call <code>ZIMGroupJoinedResult</code>.</p>
<p>Related APIs: You can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/createGroup.md">createGroup</a> to create a group, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/leaveGroup.md">leaveGroup</a> to leave a group, or <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/dismissGroup.md">dismissGroup</a> to dismiss a group.</p>
<p><code>groupID</code> The group ID to join.</p>



## Implementation

```dart
Future<ZIMGroupJoinedResult> joinGroup(String groupID);
```







