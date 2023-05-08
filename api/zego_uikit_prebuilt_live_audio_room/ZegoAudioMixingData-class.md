


# ZegoAudioMixingData class









<p>audio mixing data.</p>




## Constructors

[ZegoAudioMixingData](../zego_uikit_prebuilt_live_audio_room/ZegoAudioMixingData/ZegoAudioMixingData.md) (Uint8List audioData, int audioDataLength, [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md) param, Uint8List SEIData, int SEIDataLength)

   


## Properties

##### [audioData](../zego_uikit_prebuilt_live_audio_room/ZegoAudioMixingData/audioData.md) &#8596; Uint8List



Audio PCM data that needs to be mixed into the stream  
_<span class="feature">read / write</span>_



##### [audioDataLength](../zego_uikit_prebuilt_live_audio_room/ZegoAudioMixingData/audioDataLength.md) &#8596; int



the length of the audio PCM data that needs to be mixed into the stream. If the data length is sufficient, it must be the same as expectedDataLength  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioMixingData/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [param](../zego_uikit_prebuilt_live_audio_room/ZegoAudioMixingData/param.md) &#8596; [ZegoAudioFrameParam](../zego_uikit_prebuilt_live_audio_room/ZegoAudioFrameParam-class.md)



Audio data attributes, including sample rate and number of channels. Currently supports 16k, 32k, 44.1k, 48k sampling rate, mono or stereo, 16-bit deep PCM data. Developers need to explicitly specify audio data attributes, otherwise mixing will not take effect.  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioMixingData/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [SEIData](../zego_uikit_prebuilt_live_audio_room/ZegoAudioMixingData/SEIData.md) &#8596; Uint8List



SEI data, used to transfer custom data. When audioData is null, SEIData will not be sent  
_<span class="feature">read / write</span>_



##### [SEIDataLength](../zego_uikit_prebuilt_live_audio_room/ZegoAudioMixingData/SEIDataLength.md) &#8596; int



SEI data length  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoAudioMixingData/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoAudioMixingData/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoAudioMixingData/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















