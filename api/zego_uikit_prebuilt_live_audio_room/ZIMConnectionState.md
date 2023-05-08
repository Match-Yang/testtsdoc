


# ZIMConnectionState enum







<p>Connection state.</p>
<p>Description: The state machine that identifies the current connection state.</p>
<p>Use cases: It can be used to determine whether the login/logout is successful, and to handle abnormal situations such as network disconnection.</p>
<p>Caution: Please use it with the connection event parameter.</p>



**Inheritance**

- Object
- Enum
- ZIMConnectionState






## Constructors

[ZIMConnectionState](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState/ZIMConnectionState.md) ()

  _const_ 


## Values

##### [disconnected](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState.md) const [ZIMConnectionState](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState.md)



<p>Description: Unconnected state, enter this state before logging in and after logging out.</p>
<p>Use cases: If there is a steady state abnormality in the process of logging in, such as AppID or Token are incorrect, or if the same user name is logged in elsewhere and the local end is kicked out, it will enter this state.</p>  




##### [connecting](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState.md) const [ZIMConnectionState](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState.md)



<p>Description: The state that the connection is being requested. It will enter this state after successful execution login function.</p>
<p>Use cases: The display of the UI is usually performed using this state. If the connection is interrupted due to poor network quality, the SDK will perform an internal retry and will return to this state.</p>  




##### [connected](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState.md) const [ZIMConnectionState](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState.md)



<p>Description: The state that is successfully connected.</p>
<p>Use cases: Entering this state indicates that login successfully and the user can use the SDK functions normally.</p>  




##### [reconnecting](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState.md) const [ZIMConnectionState](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState.md)



<p>Description: The state that the reconnection is being requested. It will enter this state after successful execution login function.</p>
<p>Use cases: The display of the UI is usually performed using this state. If the connection is interrupted due to poor network quality, the SDK will perform an internal retry and will return to this state.</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState/values-constant.md) const List&lt;[ZIMConnectionState](../zego_uikit_prebuilt_live_audio_room/ZIMConnectionState.md)>



A constant List of the values in this enum, in order of their declaration.  









