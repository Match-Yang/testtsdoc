


# ZegoAudioSourceType enum







<p>Audio capture source type.</p>



**Inheritance**

- Object
- Enum
- ZegoAudioSourceType






## Constructors

[ZegoAudioSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType/ZegoAudioSourceType.md) ()

  _const_ 


## Values

##### [Default](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md) const [ZegoAudioSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md)



<p>Default audio capture source (the main channel uses custom audio capture by default; the aux channel uses the same sound as main channel by default)</p>  




##### [Custom](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md) const [ZegoAudioSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md)



<p>Use custom audio capture, refer to <code>enableCustomAudioIO</code> or <code>setAudioSource</code>. The web platform does not currently support.</p>  




##### [MediaPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md) const [ZegoAudioSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md)



<p>Use media player as audio source, only support aux channel. The web platform does not currently support.</p>  




##### [None](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md) const [ZegoAudioSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md)



<p>No audio source. This audio source type can only be used in <code>setAudioSource</code> interface, has no effect when used in <code>enableCustomAudioIO</code> interface</p>  




##### [Microphone](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md) const [ZegoAudioSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md)



<p>Using microphone as audio source. This audio source type can only be used in <code>setAudioSource</code> interface, has no effect when used in <code>enableCustomAudioIO</code> interface</p>  




##### [MainPublishChannel](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md) const [ZegoAudioSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md)



<p>Using main channel as audio source. Ineffective when used in main channel. This audio source type can only be used in <code>setAudioSource</code> interface, has no effect when used in <code>enableCustomAudioIO</code> interface. The web platform does not currently support.</p>  




##### [ScreenCapture](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md) const [ZegoAudioSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md)



<p>Using screen capture as audio source. It is only supported for iOS platform. This audio source type can only be used in <code>setAudioSource</code> interface, has no effect when used in <code>enableCustomAudioIO</code> interface</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType/values-constant.md) const List&lt;[ZegoAudioSourceType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioSourceType.md)>



A constant List of the values in this enum, in order of their declaration.  









