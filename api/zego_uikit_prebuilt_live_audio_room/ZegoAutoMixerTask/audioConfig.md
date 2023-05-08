


# audioConfig property







[ZegoMixerAudioConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoMixerAudioConfig-class.md) audioConfig
  
_<span class="feature">read / write</span>_



<p>The audio config of the auto mixer task.Description: The audio config of the auto mixer task.Use cases: If user needs special requirements for the audio config of the auto stream mixing task, such as adjusting the audio bitrate, user can set this parameter as required. Otherwise, user do not need to set this parameter.Required: No.Default value: The default audio bitrate is <code>48 kbps</code>, the default audio channel is <code>ZEGO_AUDIO_CHANNEL_MONO</code>, the default encoding ID is <code>ZEGO_AUDIO_CODEC_ID_DEFAULT</code>, and the default multi-channel audio stream mixing mode is <code>ZEGO_AUDIO_MIX_MODE_RAW</code>.Recommended value: Set this parameter based on requirements.</p>



## Implementation

```dart
ZegoMixerAudioConfig audioConfig;
```







