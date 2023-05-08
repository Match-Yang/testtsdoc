


# updateGroupNotice method








Future&lt;[ZIMGroupNoticeUpdatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupNoticeUpdatedResult-class.md)> updateGroupNotice
(String groupNotice, String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: When a group is created, users can use this method to update the group bulletin.</p>
<p>Use cases: You need to update the group bulletin in the group.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: Only group members can update the group bulletin. The maximum number of bytes is 300. There is no special character limit.</p>
<p><code>groupID</code> The group ID of the group announcement that will be updated.
<code>groupNotice</code> Pre-updated group announcements.</p>



## Implementation

```dart
Future<ZIMGroupNoticeUpdatedResult> updateGroupNotice(
    String groupNotice, String groupID);
```







