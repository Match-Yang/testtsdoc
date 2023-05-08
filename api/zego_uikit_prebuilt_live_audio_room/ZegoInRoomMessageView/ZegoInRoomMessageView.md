


# ZegoInRoomMessageView constructor






const
ZegoInRoomMessageView({Key? key, required Stream&lt;List&lt;[ZegoInRoomMessage](../../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessage-class.md)>> stream, required [ZegoInRoomMessageItemBuilder](../../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessageItemBuilder.md) itemBuilder, bool scrollable = true, ScrollController? scrollController, List&lt;[ZegoInRoomMessage](../../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessage-class.md)> historyMessages = const []})





## Implementation

```dart
const ZegoInRoomMessageView({
  Key? key,
  required this.stream,
  required this.itemBuilder,
  this.scrollable = true,
  this.scrollController,
  this.historyMessages = const [],
}) : super(key: key);
```







