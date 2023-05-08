


# ZegoMixerOutputVideoConfig class









<p>Mix stream output video config object.</p>
<p>Description: Configure the video parameters, coding format and bitrate of mix stream output.
Use cases: Manual mixed stream scenario, such as Co-hosting.</p>




## Constructors

[ZegoMixerOutputVideoConfig](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutputVideoConfig/ZegoMixerOutputVideoConfig.md) ([ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) videoCodecID, int bitrate, {[ZegoEncodeProfile](../zego_uikit_prebuilt_live_audio_room/ZegoEncodeProfile.md) encodeProfile = ZegoEncodeProfile.Default, int encodeLatency = 0})

   


## Properties

##### [bitrate](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutputVideoConfig/bitrate.md) &#8596; int



Mix stream output video bitrate in kbps. The default value is the bitrate configured in <a href="../zego_uikit_prebuilt_live_audio_room/ZegoMixerVideoConfig-class.md">ZegoMixerVideoConfig</a>.  
_<span class="feature">read / write</span>_



##### [encodeLatency](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutputVideoConfig/encodeLatency.md) &#8596; int



The video encoding delay of mixed stream output, Valid value range <code>0, 2000</code>, in milliseconds. The default value is 0.  
_<span class="feature">read / write</span>_



##### [encodeProfile](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutputVideoConfig/encodeProfile.md) &#8596; [ZegoEncodeProfile](../zego_uikit_prebuilt_live_audio_room/ZegoEncodeProfile.md)



Mix stream video encode profile. Default value is <code>ZegoEncodeProfileDefault</code>.  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutputVideoConfig/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutputVideoConfig/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [videoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutputVideoConfig/videoCodecID.md) &#8596; [ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md)



Mix stream output video coding format, supporting H.264 and h.265 coding.  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutputVideoConfig/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutputVideoConfig/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoMixerOutputVideoConfig/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















