


# ZegoMixerTask class









<p>Mix stream task object.</p>
<p>This class is the configuration class of the stream mixing task. When a stream mixing task is requested to the ZEGO RTC server, the configuration of the stream mixing task is required.
This class describes the detailed configuration information of this stream mixing task.</p>




## Constructors

[ZegoMixerTask](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/ZegoMixerTask.md) (String taskID)

Create a mix stream task object with TaskID   


## Properties

##### [advancedConfig](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/advancedConfig.md) &#8596; Map&lt;String, String>



Set advanced configuration, such as specifying video encoding and others. If you need to use it, contact ZEGO technical support.  
_<span class="feature">read / write</span>_



##### [audioConfig](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/audioConfig.md) &#8596; [ZegoMixerAudioConfig](../zego_uikit_prebuilt_live_audio_room/ZegoMixerAudioConfig-class.md)



The audio config of the task  
_<span class="feature">read / write</span>_



##### [backgroundImageURL](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/backgroundImageURL.md) &#8596; String



The background image URL of the task  
_<span class="feature">read / write</span>_



##### [enableSoundLevel](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/enableSoundLevel.md) &#8596; bool



Enable or disable sound level callback for the task. If enabled, then the remote player can get the soundLevel of every stream in the inputlist by <code>onMixerSoundLevelUpdate</code> callback.  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [inputList](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/inputList.md) &#8596; List&lt;[ZegoMixerInput](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput-class.md)>



The input list of the task  
_<span class="feature">read / write</span>_



##### [minPlayStreamBufferLength](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/minPlayStreamBufferLength.md) &#8596; int



Sets the lower limit of the interval range for the adaptive adjustment of the stream playing cache of the stream mixing server. In the real-time chorus KTV scenario, slight fluctuations in the network at the push end may cause the mixed stream to freeze. At this time, when the audience pulls the mixed stream, there is a high probability of the problem of freeze. By adjusting the lower limit of the interval range for the adaptive adjustment of the stream playing cache of the stream mixing server, it can optimize the freezing problem that occurs when playing mixing streams at the player end, but it will increase the delay. It is not set by default, that is, the server uses its own configuration values. It only takes effect for the new input stream setting, and does not take effect for the input stream that has already started mixing.  
_<span class="feature">read / write</span>_



##### [outputList](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/outputList.md) &#8596; List&lt;[ZegoMixerOutput](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutput-class.md)>



The output list of the task  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [taskID](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/taskID.md) &#8596; String



The task ID of the task  
_<span class="feature">read / write</span>_



##### [videoConfig](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/videoConfig.md) &#8596; [ZegoMixerVideoConfig](../zego_uikit_prebuilt_live_audio_room/ZegoMixerVideoConfig-class.md)



The audio config of the task  
_<span class="feature">read / write</span>_



##### [watermark](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/watermark.md) &#8596; [ZegoWatermark](../zego_uikit_prebuilt_live_audio_room/ZegoWatermark-class.md)



The watermark of the task  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toMap](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/toMap.md)() Map&lt;String, dynamic>



  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoMixerTask/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















