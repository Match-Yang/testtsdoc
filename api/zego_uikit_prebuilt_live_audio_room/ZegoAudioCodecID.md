


# ZegoAudioCodecID enum







<p>Audio codec ID.</p>



**Inheritance**

- Object
- Enum
- ZegoAudioCodecID






## Constructors

[ZegoAudioCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID/ZegoAudioCodecID.md) ()

  _const_ 


## Values

##### [Default](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md) const [ZegoAudioCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md)



<p>Default, determined by the <code>scenario</code> when calling <code>createEngine</code>.</p>  




##### [Normal](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md) const [ZegoAudioCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md)



<p>Can be used for RTC and CDN streaming; bitrate range from 10kbps to 128kbps; supports stereo; latency is around 500ms. Server cloud transcoding is required when communicating with the Web SDK, and it is not required when relaying to CDN.</p>  




##### [Normal2](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md) const [ZegoAudioCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md)



<p>Can be used for RTC and CDN streaming; good compatibility; bitrate range from 16kbps to 192kbps; supports stereo; latency is around 350ms; the sound quality is worse than <a href="../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md">Normal</a> in the same (low) bitrate. Server cloud transcoding is required when communicating with the Web SDK, and it is not required when relaying to CDN.</p>  




##### [Normal3](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md) const [ZegoAudioCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md)



<p>Not recommended; if you need to use it, please contact ZEGO technical support. Can only be used for RTC streaming.</p>  




##### [Low](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md) const [ZegoAudioCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md)



<p>Not recommended; if you need to use it, please contact ZEGO technical support. Can only be used for RTC streaming.</p>  




##### [Low2](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md) const [ZegoAudioCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md)



<p>Not recommended; if you need to use it, please contact ZEGO technical support. Can only be used for RTC streaming; maximum bitrate is 16kbps.</p>  




##### [Low3](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md) const [ZegoAudioCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md)



<p>Can only be used for RTC streaming; bitrate range from 6kbps to 192kbps; supports stereo; latency is around 200ms; Under the same bitrate (low bitrate), the sound quality is significantly better than <a href="../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md">Normal</a> and <a href="../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md">Normal2</a>; low CPU overhead. Server cloud transcoding is not required when communicating with the Web SDK, and it is required when relaying to CDN.</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID/values-constant.md) const List&lt;[ZegoAudioCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoAudioCodecID.md)>



A constant List of the values in this enum, in order of their declaration.  









