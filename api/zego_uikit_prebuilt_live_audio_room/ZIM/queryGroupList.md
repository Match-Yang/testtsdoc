


# queryGroupList method








Future&lt;[ZIMGroupListQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupListQueriedResult-class.md)> queryGroupList
()





<p>Available since: 2.1.5 and above.</p>
<p>Description: Query the list of all groups.</p>
<p>Use cases: You need to get a list of groups to display.</p>
<p>When to call /Trigger: The ZIM instance can be invoked after being created by <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and logged in.</p>
<p>Restrictions: Available after login, unavailable after logout.</p>



## Implementation

```dart
Future<ZIMGroupListQueriedResult> queryGroupList();
```







