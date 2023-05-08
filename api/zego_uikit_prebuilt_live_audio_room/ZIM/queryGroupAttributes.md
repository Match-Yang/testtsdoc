


# queryGroupAttributes method








Future&lt;[ZIMGroupAttributesQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupAttributesQueriedResult-class.md)> queryGroupAttributes
(List&lt;String> keys, String groupID)





<p>Available since: 2.1.5 and above.</p>
<p>Description: After a group is created, you can use this method to query the specified group properties.</p>
<p>Use cases: You need to query the scenarios to display the specified group attributes.</p>
<p>When to call /Trigger: After creating a ZIM instance with <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logging in with <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/login.md">login</a>.</p>
<p>Restrictions: Available after login, unavailable after logout.</p>
<p>Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupAllAttributes.md">queryGroupAllAttributes</a> Queries all group attributes.</p>
<p><code>keys</code> The key of the group attribute to be queried.
 <code>groupID</code> The group ID of the group attribute to be queried.</p>



## Implementation

```dart
Future<ZIMGroupAttributesQueriedResult> queryGroupAttributes(
    List<String> keys, String groupID);
```







