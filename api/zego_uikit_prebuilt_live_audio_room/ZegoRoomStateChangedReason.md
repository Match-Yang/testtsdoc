


# ZegoRoomStateChangedReason enum







<p>Room state change reason.</p>



**Inheritance**

- Object
- Enum
- ZegoRoomStateChangedReason






## Constructors

[ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason/ZegoRoomStateChangedReason.md) ()

  _const_ 


## Values

##### [Logining](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md) const [ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md)



<p>Logging in to the room. When calling <code>loginRoom</code> to log in to the room or <code>switchRoom</code> to switch to the target room, it will enter this state, indicating that it is requesting to connect to the server. The application interface is usually displayed through this state.</p>  




##### [Logined](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md) const [ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md)



<p>Log in to the room successfully. When the room is successfully logged in or switched, it will enter this state, indicating that the login to the room has been successful, and users can normally receive callback notifications of other users in the room and all stream information additions and deletions.</p>  




##### [LoginFailed](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md) const [ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md)



<p>Failed to log in to the room. When the login or switch room fails, it will enter this state, indicating that the login or switch room has failed, for example, AppID or Token is incorrect, etc.</p>  




##### [Reconnecting](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md) const [ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md)



<p>The room connection is temporarily interrupted. If the interruption occurs due to poor network quality, the SDK will retry internally.</p>  




##### [Reconnected](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md) const [ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md)



<p>The room is successfully reconnected. If there is an interruption due to poor network quality, the SDK will retry internally, and enter this state after successful reconnection.</p>  




##### [ReconnectFailed](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md) const [ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md)



<p>The room fails to reconnect. If there is an interruption due to poor network quality, the SDK will retry internally, and enter this state after the reconnection fails.</p>  




##### [KickOut](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md) const [ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md)



<p>Kicked out of the room by the server. For example, if you log in to the room with the same user name in other places, and the local end is kicked out of the room, it will enter this state.</p>  




##### [Logout](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md) const [ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md)



<p>Logout of the room is successful. It is in this state by default before logging into the room. When calling <code>logoutRoom</code> to log out of the room successfully or <code>switchRoom</code> to log out of the current room successfully, it will enter this state.</p>  




##### [LogoutFailed](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md) const [ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md)



<p>Failed to log out of the room. Enter this state when calling <code>logoutRoom</code> fails to log out of the room or <code>switchRoom</code> fails to log out of the current room internally.</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason/values-constant.md) const List&lt;[ZegoRoomStateChangedReason](../zego_uikit_prebuilt_live_audio_room/ZegoRoomStateChangedReason.md)>



A constant List of the values in this enum, in order of their declaration.  









