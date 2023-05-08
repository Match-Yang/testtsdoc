


# vad property







int vad
  
_<span class="feature">read / write</span>_



<p>Whether the stream corresponding to StreamID contains voice, 0 means noise, 1 means normal voice. This value is valid only when the <code>enableVAD</code> parameter in the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoSoundLevelConfig-class.md">ZegoSoundLevelConfig</a> configuration is set to true when calling <code>startSoundLevelMonitor</code>.</p>



## Implementation

```dart
int vad;
```







