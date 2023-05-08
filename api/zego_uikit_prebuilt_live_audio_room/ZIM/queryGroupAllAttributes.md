


# queryGroupAllAttributes method








Future&lt;[ZIMGroupAttributesQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupAttributesQueriedResult-class.md)> queryGroupAllAttributes
(String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a group is created, you can use this method to query all group attributes.</p>
<p>Use cases: Scenarios where all group attributes need to be queried.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Related callbacks: Through callback can get query <code>ZIMGroupAttributesQueriedResult</code> all the results of the group of attributes.</p>
<p>Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupAttributes.md">queryGroupAttributes</a> Queries the attributes of the specified group.</p>
<p><code>groupID</code> The group ID of all group attributes to be queried.</p>



## Implementation

```dart
Future<ZIMGroupAttributesQueriedResult> queryGroupAllAttributes(
    String groupID);
```







