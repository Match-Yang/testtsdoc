


# ZIMRoomState enum







<p>Connection state.</p>
<p>Description: The state machine that identifies the current connection state.</p>
<p>Use cases: It can be used to judge whether the user enters/exit the room successfully, and handles abnormal situations such as network disconnection.</p>
<p>Caution: Please use it with the connection event parameter.</p>



**Inheritance**

- Object
- Enum
- ZIMRoomState






## Constructors

[ZIMRoomState](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState/ZIMRoomState.md) ()

  _const_ 


## Values

##### [disconnected](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState.md) const [ZIMRoomState](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState.md)



<p>Description: Disconnected state.</p>
<p>Use cases: enter this state before entering the room and after exiting the room.</p>  




##### [connecting](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState.md) const [ZIMRoomState](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState.md)



<p>Description: The connection state is being requested.</p>
<p>Use cases: and it will enter this state after the action of entering the room is executed successfully. The application interface is usually displayed through this state.</p>  




##### [connected](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState.md) const [ZIMRoomState](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState.md)



<p>Description: The connection is successful.</p>
<p>Use cases: Entering this state means that the room has been successfully entered, and the user can use the room's functions normally.</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState/values-constant.md) const List&lt;[ZIMRoomState](../zego_uikit_prebuilt_live_audio_room/ZIMRoomState.md)>



A constant List of the values in this enum, in order of their declaration.  









