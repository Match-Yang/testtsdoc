


# ZegoUIKitPrebuiltLiveAudioRoomConfig.audience constructor







ZegoUIKitPrebuiltLiveAudioRoomConfig.audience()


<p>audience 默认的初始化参数。如果某个配置项不符合你的预期，你可以直接覆盖这个配置项的值。</p>
<p>Example:</p>
<pre class="language-dart"><code class="language-dart">ZegoUIKitPrebuiltLiveAudioRoomConfig.audience()
..hostSeatIndexes = [0]
</code></pre>



## Implementation

```dart
ZegoUIKitPrebuiltLiveAudioRoomConfig.audience()
    : role = ZegoLiveAudioRoomRole.audience,
      turnOnMicrophoneWhenJoining = false,
      closeSeatsWhenJoining = false,
      useSpeakerWhenJoining = true,
      userInRoomAttributes = const {},
      seatConfig = ZegoLiveAudioRoomSeatConfig(),
      layoutConfig = ZegoLiveAudioRoomLayoutConfig(),
      hostSeatIndexes = const [0],
      topMenuBarConfig = ZegoTopMenuBarConfig(),
      bottomMenuBarConfig = ZegoBottomMenuBarConfig(),
      inRoomMessageViewConfig = ZegoInRoomMessageViewConfig(),
      audioEffectConfig = ZegoAudioEffectConfig(),
      innerText = ZegoInnerText();
```







