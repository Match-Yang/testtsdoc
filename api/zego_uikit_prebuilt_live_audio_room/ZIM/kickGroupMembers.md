


# kickGroupMembers method








Future&lt;[ZIMGroupMemberKickedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberKickedResult-class.md)> kickGroupMembers
(List&lt;String> userIDs, String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a user joins a group, you can use this method to remove the user from the group.</p>
<p>Use cases: You can use this method to remove one or more users from the group.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: You can't kick someone unless you're the leader of the group.</p>
<p>Caution: This interface does not require the peer's consent or the peer's online status. It cannot accept group-related callbacks after being kicked out. History messages and sessions remain after being kicked out and can still enter the group.</p>
<p>Related callbacks: Through the callback <code>ZIMGroupMemberKickedResult</code> can get the user kicked out the results of the group.</p>
<p>Related APIs: You can invite a target user into a group through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/inviteUsersIntoGroup.md">inviteUsersIntoGroup</a>.</p>
<p><code>groupID</code> The group ID of the member who will be kicked out.
<code>userIDs</code> List of users who have been kicked out of the group.</p>



## Implementation

```dart
Future<ZIMGroupMemberKickedResult> kickGroupMembers(
    List<String> userIDs, String groupID);
```







