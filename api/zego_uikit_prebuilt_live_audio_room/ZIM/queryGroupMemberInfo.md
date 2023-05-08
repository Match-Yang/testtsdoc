


# queryGroupMemberInfo method








Future&lt;[ZIMGroupMemberInfoQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberInfoQueriedResult-class.md)> queryGroupMemberInfo
(String userID, String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a group is created, you can use this method to query information about a specified group member.</p>
<p>Use cases: You need to obtain the specified group member information for display or interaction.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: Available after login, unavailable after logout.</p>
<p><code>userID</code> User ID of the queried member information.
<code>groupID</code> The ID of the group whose member information will be queried.</p>



## Implementation

```dart
Future<ZIMGroupMemberInfoQueriedResult> queryGroupMemberInfo(
    String userID, String groupID);
```







