


# queryGroupMemberList method








Future&lt;[ZIMGroupMemberListQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberListQueriedResult-class.md)> queryGroupMemberList
(String groupID, [ZIMGroupMemberQueryConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberQueryConfig-class.md) config)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a group is created, you can use this method to query the group member list.</p>
<p>Use cases: You need to obtain the specified group member list for display or interaction.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: Available after login, unavailable after logout.</p>
<p><code>groupID</code> The group ID of the group member list to be queried.
<code>config</code> Group member query configuration.</p>



## Implementation

```dart
Future<ZIMGroupMemberListQueriedResult> queryGroupMemberList(
    String groupID, ZIMGroupMemberQueryConfig config);
```







