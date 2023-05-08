


# transferGroupOwner method








Future&lt;[ZIMGroupOwnerTransferredResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupOwnerTransferredResult-class.md)> transferGroupOwner
(String toUserID, String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a group is created, the group owner can use this method to assign the group owner to a specified user.</p>
<p>Use cases: In a group chat scenario, you can transfer the group master through this interface.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: You cannot transfer a group owner if you are not a group owner.</p>
<p>Related APIs: Through the callback <code>ZIMGroupOwnerTransferredResult</code> can get the result of the transfer of the group manager.
<code>toUserID</code> The converted group owner ID.
<code>groupID</code> The group ID of the group owner to be replaced.</p>



## Implementation

```dart
Future<ZIMGroupOwnerTransferredResult> transferGroupOwner(
    String toUserID, String groupID);
```







