


# setGroupAttributes method








Future&lt;[ZIMGroupAttributesOperatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupAttributesOperatedResult-class.md)> setGroupAttributes
(Map&lt;String, String> groupAttributes, String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: If a group already exists, all users of the group can use this method to set group properties.</p>
<p>Use cases: Added extended field information about group description, such as group family, label, and industry category.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: Only group members can set group properties.</p>
<p>Related callbacks: Through the callback <code>ZIMGroupAttributesOperatedResult</code> can get the result of the set of properties.</p>
<p>Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteGroupAttributes.md">deleteGroupAttributes</a> can be used to deleteGroupAttributes, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupAttributes.md">queryGroupAttributes</a> can be used to queryGroupAttributes, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupAllAttributes.md">queryGroupAllAttributes</a> can be used to queryAllGroupAttributes.</p>
<p><code>groupAttributes</code> group properties.
<code>groupID</code> groupID.</p>



## Implementation

```dart
Future<ZIMGroupAttributesOperatedResult> setGroupAttributes(
    Map<String, String> groupAttributes, String groupID);
```







