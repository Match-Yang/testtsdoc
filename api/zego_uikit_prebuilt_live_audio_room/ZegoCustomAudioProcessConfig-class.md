


# ZegoCustomAudioProcessConfig class









<p>Customize the audio processing configuration object.</p>
<p>Including custom audio acquisition type, sampling rate, channel number, sampling number and other parameters</p>




## Constructors

[ZegoCustomAudioProcessConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig/ZegoCustomAudioProcessConfig.md) ([ZegoAudioSampleRate](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSampleRate.md) sampleRate, [ZegoAudioChannel](../zego_uikit_prebuilt_live_audio_room/ZegoAudioChannel.md) channel, int samples)

   

[ZegoCustomAudioProcessConfig.defaultConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig/ZegoCustomAudioProcessConfig.defaultConfig.md) ()

   


## Properties

##### [channel](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig/channel.md) &#8596; [ZegoAudioChannel](../zego_uikit_prebuilt_live_audio_room/ZegoAudioChannel.md)



Number of sound channels, the expected number of sound channels for input data of the audio pre-processing module in App. If 0, the default is the number of internal channels in the SDK  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [sampleRate](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig/sampleRate.md) &#8596; [ZegoAudioSampleRate](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSampleRate.md)



Sampling rate, the sampling rate of the input data expected by the audio pre-processing module in App. If 0, the default is the SDK internal sampling rate.  
_<span class="feature">read / write</span>_



##### [samples](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig/samples.md) &#8596; int



The number of samples required to encode a frame; if samples = 0, the SDK will use the internal sample number, and the SDK will pass the audio data to the external pre-processing module. If the samples! = 0 (the effective value of samples is between <code>160, 2048</code>), and the SDK will send audio data to the external preprocessing module that sets the length of sample number.  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoCustomAudioProcessConfig/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















