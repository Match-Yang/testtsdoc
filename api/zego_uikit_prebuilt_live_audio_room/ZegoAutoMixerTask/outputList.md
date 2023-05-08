


# outputList property







List&lt;[ZegoMixerOutput](../../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutput-class.md)> outputList
  
_<span class="feature">read / write</span>_



<p>The output list of the auto mixer task.Description: The output list of the auto stream mixing task, items in the list are URL or stream ID, if the item set to be URL format, only RTMP URL surpported, for example rtmp://xxxxxxxx.Use cases: User need to set this parameter to specify the mix stream output target when starting an auto stream mixing task.Required: Yes.</p>



## Implementation

```dart
List<ZegoMixerOutput> outputList;
```







