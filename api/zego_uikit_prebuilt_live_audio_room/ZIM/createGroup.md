


# createGroup method








Future&lt;[ZIMGroupCreatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupCreatedResult-class.md)> createGroup
([ZIMGroupInfo](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupInfo-class.md) groupInfo, List&lt;String> userIDs, [[ZIMGroupAdvancedConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMGroupAdvancedConfig-class.md)? config])





<p>Available since: 2.1.5 and above.</p>
<p>Description: You can call this interface to create a group, and the person who calls this interface is the group leader. An empty string if the group name is left blank.</p>
<p>Use cases: You can use this interface to create a chat scenario and join a group.</p>
<p>When to call: After you create a ZIM instance with <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and login with <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/login.md">login</a>.</p>
<p>Restrictions: Available after login, unavailable after logout. UserIDs support a maximum of 100 users and a group supports a maximum of 500 users.</p>
<p>Impacts on other APIs: You can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/joinGroup.md">joinGroup</a> to join a group, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/leaveGroup.md">leaveGroup</a> to leave a group, or <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/dismissGroup.md">dismissGroup</a> to dismiss a group.</p>
<p><code>groupInfo</code> Configuration information for the group to be created.
<code>userIDs</code> List of users invited to the group.
<code>config</code>  Create the relevant configuration of the group.</p>



## Implementation

```dart
Future<ZIMGroupCreatedResult> createGroup(
    ZIMGroupInfo groupInfo, List<String> userIDs,
    [ZIMGroupAdvancedConfig? config]);
```







