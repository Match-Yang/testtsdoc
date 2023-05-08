


# deleteGroupAttributes method








Future&lt;[ZIMGroupAttributesOperatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupAttributesOperatedResult-class.md)> deleteGroupAttributes
(List&lt;String> keys, String groupID)





<p>Available since: 2.0.0 and above.</p>
<p>Description: When a group already exists, you can use this method to delete group attributes. Both the master and members of the interface group can be invoked.</p>
<p>Use cases: Deleted the extended field of the group description.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: Only group members can delete group attributes.</p>
<p>Related callbacks: Through the callback <code>ZIMGroupAttributesOperatedResult</code> can delete the result of the group of attributes.</p>
<p>Related APIs: You can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/setGroupAttributes.md">setGroupAttributes</a> to setGroupAttributes, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupAttributes.md">queryGroupAttributes</a> to queryGroupAttributes, and <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupAllAttributes.md">queryGroupAllAttributes</a> to queryAllGroupAttributes.</p>
<p><code>groupID</code>  The group ID of the group attribute to be deleted.
<code>keys</code> The key of the group attribute to delete.</p>



## Implementation

```dart
Future<ZIMGroupAttributesOperatedResult> deleteGroupAttributes(
    List<String> keys, String groupID);
```







