


# ZegoUIKitPrebuiltLiveAudioRoomConfig.host constructor







ZegoUIKitPrebuiltLiveAudioRoomConfig.host()


<p>Host 默认的初始化参数。如果某个配置项不符合你的预期，你可以直接覆盖这个配置项的值。</p>
<p>Example:</p>
<pre class="language-dart"><code class="language-dart">ZegoUIKitPrebuiltLiveAudioRoomConfig.host()
..hostSeatIndexes = [0]
</code></pre>



## Implementation

```dart
ZegoUIKitPrebuiltLiveAudioRoomConfig.host()
    : role = ZegoLiveAudioRoomRole.host,
      takeSeatIndexWhenJoining = 0,
      closeSeatsWhenJoining = true,
      turnOnMicrophoneWhenJoining = true,
      useSpeakerWhenJoining = true,
      userInRoomAttributes = const {},
      seatConfig = ZegoLiveAudioRoomSeatConfig(),
      layoutConfig = ZegoLiveAudioRoomLayoutConfig(),
      hostSeatIndexes = const [0],
      topMenuBarConfig = ZegoTopMenuBarConfig(),
      bottomMenuBarConfig = ZegoBottomMenuBarConfig(),
      inRoomMessageViewConfig = ZegoInRoomMessageViewConfig(),
      audioEffectConfig = ZegoAudioEffectConfig(),
      innerText = ZegoInnerText(),
      confirmDialogInfo = ZegoDialogInfo(
        title: 'Leave the room',
        message: 'Are you sure to leave the room?',
        cancelButtonName: 'Cancel',
        confirmButtonName: 'OK',
      );
```







