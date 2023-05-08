


# queryConversationList method








Future&lt;[ZIMConversationListQueriedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationListQueriedResult-class.md)> queryConversationList
([ZIMConversationQueryConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMConversationQueryConfig-class.md) config)





<p>Available since: 2.1.5 and above.
Description: This method displays the session list of the logged in user.
Use cases: This interface can be invoked to get the data source when you need to display an existing message session after logging in.</p>
<p>When to call /Trigger: Can be invoked after login.</p>
<p>Restrictions:There is no limit to the frequency of use, available after login, unavailable after logout.</p>
<p>Caution: NextConversation is the riveting point of the query message, which can be null for the first query. In subsequent query, the earliest conversation can be used as nextConversation to query earlier sessions. In paging query, Count in <a href="../../zego_uikit_prebuilt_live_audio_room/ZIMConversationQueryConfig-class.md">ZIMConversationQueryConfig</a> fill each pull the number of sessions.</p>
<p>Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/deleteConversation.md">deleteConversation</a> Deletes the session. <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/clearConversationUnreadMessageCount.md">clearConversationUnreadMessageCount</a> clear session readings.</p>
<p><code>config</code> Configuration for session queries.</p>



## Implementation

```dart
/// Description: This method displays the session list of the logged in user.

/// Use cases: This interface can be invoked to get the data source when you need to display an existing message session after logging in.
///
/// When to call /Trigger: Can be invoked after login.
///
/// Restrictions:There is no limit to the frequency of use, available after login, unavailable after logout.
///
/// Caution: NextConversation is the riveting point of the query message, which can be null for the first query. In subsequent query, the earliest conversation can be used as nextConversation to query earlier sessions. In paging query, Count in [ZIMConversationQueryConfig] fill each pull the number of sessions.
///
/// Related APIs: [deleteConversation] Deletes the session. [clearConversationUnreadMessageCount] clear session readings.
///
/// [config] Configuration for session queries.
Future<ZIMConversationListQueriedResult> queryConversationList(
    ZIMConversationQueryConfig config);
```







