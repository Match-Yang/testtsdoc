


# leaveGroup method








Future&lt;[ZIMGroupLeftResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupLeftResult-class.md)> leaveGroup
(String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a user joins a group, the user can leave the group through this interface.</p>
<p>Use cases: This interface is used to exit a chat group.</p>
<p>When to call /Trigger: It can be invoked after a ZIM instance is created through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: Available after login, unavailable after logout.</p>
<p>Caution: When the group owner quits the group, the identity of the group owner will be automatically transferred to the earliest member who joined the group. When all members exit the group, the group is automatically dissolved.</p>
<p>Impacts on other APIs: You can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/createGroup.md">createGroup</a> to create a group, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/joinGroup.md">joinGroup</a> to join a group, or <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/dismissGroup.md">dismissGroup</a> to dismiss a group.</p>
<p><code>groupID</code> The group ID to leave.</p>



## Implementation

```dart
Future<ZIMGroupLeftResult> leaveGroup(String groupID);
```







