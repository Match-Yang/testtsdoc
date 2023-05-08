


# inviteUsersIntoGroup method








Future&lt;[ZIMGroupUsersInvitedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupUsersInvitedResult-class.md)> inviteUsersIntoGroup
(List&lt;String> userIDs, String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a group is created, users can add multiple users to the group through this interface. The interface can be invoked by both the master and members of the group.</p>
<p>Use cases: This interface allows you to invite others to join a group chat.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: The maximum number of userIDs users can join the group is 100. If the number of users reaches 100, the interface callback will notify the user. The maximum number of people in a group is 500.</p>
<p>Caution: This interface does not require the peer's consent or the peer's online status. The service layer determines the number of invited users.</p>
<p>Related callbacks: Through the callback <code>ZIMGroupUsersInvitedResult</code> can add multiple users into the group's results.</p>
<p>Related APIs: KickGroupMember can be used to kick a target user out of the group.
<code>groupID</code> The ID of the group that will invite users to the group.
<code>userIDs</code> List of invited users.</p>



## Implementation

```dart
Future<ZIMGroupUsersInvitedResult> inviteUsersIntoGroup(
    List<String> userIDs, String groupID);
```







