


# dismissGroup method








Future&lt;[ZIMGroupDismissedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupDismissedResult-class.md)> dismissGroup
(String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: When a group is created, you can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/dismissGroup.md">dismissGroup</a> to dismiss it.</p>
<p>Use cases: After you create a chat group, you do not need to use this interface to dissolve the group.</p>
<p>When to call /Trigger: This parameter can be called after a group is created by using <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/createGroup.md">createGroup</a>.</p>
<p>Caution: A non-group owner cannot dissolve a group.</p>
<p>Impacts on other APIs: Through callback can get <code>ZIMGroupDismissedResult</code> dissolution results of the room, through <code>ZIMEventHandler.onGroupStateChanged</code> listen callback can get the room status.</p>
<p>Related callbacks: You can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/createGroup.md">createGroup</a> to create a group, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/joinGroup.md">joinGroup</a> to join a group, and <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/leaveGroup.md">leaveGroup</a> to leave a group.</p>
<p><code>groupID</code> The ID of the group to be disbanded.</p>



## Implementation

```dart
Future<ZIMGroupDismissedResult> dismissGroup(String groupID);
```







