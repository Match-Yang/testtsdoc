


# ZegoRoomState enum







<p>Room state.</p>



**Inheritance**

- Object
- Enum
- ZegoRoomState






## Constructors

[ZegoRoomState](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState/ZegoRoomState.md) ()

  _const_ 


## Values

##### [Disconnected](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState.md) const [ZegoRoomState](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState.md)



<p>Unconnected state, enter this state before logging in and after exiting the room. If there is a steady state abnormality in the process of logging in to the room, such as AppID or Token are incorrect, or if the same user name is logged in elsewhere and the local end is KickOut, it will enter this state.</p>  




##### [Connecting](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState.md) const [ZegoRoomState](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState.md)



<p>The state that the connection is being requested. It will enter this state after successful execution login room function. The display of the UI is usually performed using this state. If the connection is interrupted due to poor network quality, the SDK will perform an internal retry and will return to the requesting connection status.</p>  




##### [Connected](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState.md) const [ZegoRoomState](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState.md)



<p>The status that is successfully connected. Entering this status indicates that the login to the room has been successful. The user can receive the callback notification of the user and the stream information in the room.</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState/values-constant.md) const List&lt;[ZegoRoomState](../zego_uikit_prebuilt_live_audio_room/ZegoRoomState.md)>



A constant List of the values in this enum, in order of their declaration.  









