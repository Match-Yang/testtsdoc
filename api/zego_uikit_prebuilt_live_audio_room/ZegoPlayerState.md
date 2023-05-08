


# ZegoPlayerState enum







<p>Playing stream status.</p>



**Inheritance**

- Object
- Enum
- ZegoPlayerState






## Constructors

[ZegoPlayerState](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState/ZegoPlayerState.md) ()

  _const_ 


## Values

##### [NoPlay](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState.md) const [ZegoPlayerState](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState.md)



<p>The state of the flow is not played, and it is in this state before the stream is played. If the steady flow anomaly occurs during the playing process, such as AppID or Token are incorrect, it will enter this state.</p>  




##### [PlayRequesting](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState.md) const [ZegoPlayerState](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState.md)



<p>The state that the stream is being requested for playing. After the <code>startPlayingStream</code> function is successfully called, it will enter the state. The UI is usually displayed through this state. If the connection is interrupted due to poor network quality, the SDK will perform an internal retry and will return to the requesting state.</p>  




##### [Playing](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState.md) const [ZegoPlayerState](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState.md)



<p>The state that the stream is being playing, entering the state indicates that the stream has been successfully played, and the user can communicate normally.</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState/values-constant.md) const List&lt;[ZegoPlayerState](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerState.md)>



A constant List of the values in this enum, in order of their declaration.  









