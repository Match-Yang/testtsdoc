


# setRoomMembersAttributes method








Future&lt;[ZIMRoomMembersAttributesOperatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomMembersAttributesOperatedResult-class.md)> setRoomMembersAttributes
(Map&lt;String, String> attributes, List&lt;String> userIDs, String roomID, [ZIMRoomMemberAttributesSetConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberAttributesSetConfig-class.md) config)





<p>Supported Versions: 2.4.0 and above.</p>
<p>Detail description: Call this API to set room user properties of members in the room.</p>
<p>Business scenario: If you need to set a level for members in the room, you can use this interface to set a state.</p>
<p>Default: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberAttributesSetConfig-class.md">ZIMRoomMemberAttributesSetConfig</a> Default constructor isDeleteAfterOwnerLeft is true.</p>
<p>Call timing/Notification timing: After logging in and calling in the relevant room.</p>
<p>Usage limit: background limit, default 20</p>
<p>Related interfaces: <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryRoomMembersAttributes.md">queryRoomMembersAttributes</a>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/queryRoomMemberAttributesList.md">queryRoomMemberAttributesList</a>.
<code>attributes</code> Room member attributes to be set.
<code>userIDs</code> A list of userIDs to set.
<code>roomID</code> Room ID.
<code>config</code> Behavior configuration of the operation.</p>



## Implementation

```dart
Future<ZIMRoomMembersAttributesOperatedResult> setRoomMembersAttributes(
    Map<String, String> attributes,
    List<String> userIDs,
    String roomID,
    ZIMRoomMemberAttributesSetConfig config);
```







