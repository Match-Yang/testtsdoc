


# ZegoAutoMixerTask class









<p>Auto mix stream task object.</p>
<p>Description: When using <code>StartAutoMixerTask</code> function to start an auto stream mixing task to the ZEGO RTC server, user need to set this parameter to configure the auto stream mixing task, including the task ID, room ID, audio configuration, output stream list, and whether to enable the sound level callback.
Use cases: This configuration is required when an auto stream mixing task is requested to the ZEGO RTC server.
Caution: As an argument passed when <code>StartAutoMixerTask</code> function is called.</p>




## Constructors

[ZegoAutoMixerTask](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/ZegoAutoMixerTask.md) ()

Create a auto mix stream task object   


## Properties

##### [audioConfig](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/audioConfig.md) &#8596; [ZegoMixerAudioConfig](../zego_uikit_prebuilt_live_audio_room/ZegoMixerAudioConfig-class.md)



The audio config of the auto mixer task.Description: The audio config of the auto mixer task.Use cases: If user needs special requirements for the audio config of the auto stream mixing task, such as adjusting the audio bitrate, user can set this parameter as required. Otherwise, user do not need to set this parameter.Required: No.Default value: The default audio bitrate is <code>48 kbps</code>, the default audio channel is <code>ZEGO_AUDIO_CHANNEL_MONO</code>, the default encoding ID is <code>ZEGO_AUDIO_CODEC_ID_DEFAULT</code>, and the default multi-channel audio stream mixing mode is <code>ZEGO_AUDIO_MIX_MODE_RAW</code>.Recommended value: Set this parameter based on requirements.  
_<span class="feature">read / write</span>_



##### [enableSoundLevel](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/enableSoundLevel.md) &#8596; bool



Enable or disable sound level callback for the task. If enabled, then the remote player can get the sound level of every stream in the inputlist by <code>onAutoMixerSoundLevelUpdate</code> callback.Description: Enable or disable sound level callback for the task.If enabled, then the remote player can get the sound level of every stream in the inputlist by <code>onAutoMixerSoundLevelUpdate</code> callback.Use cases: This parameter needs to be configured if user need the sound level information of every stream when an auto stream mixing task started.Required: No.Default value: <code>false</code>.Recommended value: Set this parameter based on requirements.  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [outputList](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/outputList.md) &#8596; List&lt;[ZegoMixerOutput](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutput-class.md)>



The output list of the auto mixer task.Description: The output list of the auto stream mixing task, items in the list are URL or stream ID, if the item set to be URL format, only RTMP URL surpported, for example rtmp://xxxxxxxx.Use cases: User need to set this parameter to specify the mix stream output target when starting an auto stream mixing task.Required: Yes.  
_<span class="feature">read / write</span>_



##### [roomID](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/roomID.md) &#8596; String



The roomID of the auto mixer task.Description: Auto stream mixing task id.Use cases: User need to set this parameter when initiating an auto stream mixing task.Required: Yes.Recommended value: Set this parameter based on requirements.Value range: A string up to 128 bytes.Caution: Only support numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', '’', ',', '.', '&lt;', '&gt;', '/', ''.If you need to communicate with the Web SDK, please do not use '%'.  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [taskID](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/taskID.md) &#8596; String



The taskID of the auto mixer task.Description: Auto stream mixing task id, must be unique in a room.Use cases: User need to set this parameter when initiating an auto stream mixing task.Required: Yes.Recommended value: Set this parameter based on requirements.Value range: A string up to 256 bytes.Caution: When starting a new auto stream mixing task, only one auto stream mixing task ID can exist in a room, that is, to ensure the uniqueness of task ID. You are advised to associate task ID with room ID. You can directly use the room ID as the task ID.Cannot include URL keywords, for example, 'http' and '?' etc, otherwise publishing stream and playing stream will fail. Only support numbers, English characters and '~', '!', '@', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', '’', ',', '.', '&lt;', '&gt;', '/', ''.  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toMap](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/toMap.md)() Map&lt;String, dynamic>



  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoAutoMixerTask/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















