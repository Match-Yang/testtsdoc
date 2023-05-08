


# queryGroupInfo method








Future&lt;[ZIMGroupInfoQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupInfoQueriedResult-class.md)> queryGroupInfo
(String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: Query information about a created group.</p>
<p>Use cases: You need to obtain group information for display.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Related callbacks: Through the callback <code>ZIMGroupInfoQueriedResult</code> can query the result of the group information.</p>
<p><code>groupID</code> The group ID of the group information to be queried.</p>



## Implementation

```dart
Future<ZIMGroupInfoQueriedResult> queryGroupInfo(String groupID);
```







