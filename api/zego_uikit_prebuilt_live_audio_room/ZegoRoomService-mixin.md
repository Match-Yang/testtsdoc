


# ZegoRoomService mixin















**Mixin Applications**

- [ZegoUIKit](../zego_uikit_prebuilt_live_audio_room/ZegoUIKit-class.md)



## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [getNetworkModeStream](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getNetworkModeStream.md)() Stream&lt;[ZegoNetworkMode](../zego_uikit_prebuilt_live_audio_room/ZegoNetworkMode.md)>



get network state notifier  




##### [getRoom](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getRoom.md)() [ZegoUIKitRoom](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitRoom-class.md)



get room object  




##### [getRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getRoomProperties.md)() Map&lt;String, [RoomProperty](../zego_uikit_prebuilt_live_audio_room/RoomProperty-class.md)>



get room properties  




##### [getRoomPropertiesStream](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getRoomPropertiesStream.md)() Stream&lt;Map&lt;String, [RoomProperty](../zego_uikit_prebuilt_live_audio_room/RoomProperty-class.md)>>



only notify the properties which changed
you can get full properties by getRoomProperties() function  




##### [getRoomPropertyStream](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getRoomPropertyStream.md)() Stream&lt;[RoomProperty](../zego_uikit_prebuilt_live_audio_room/RoomProperty-class.md)>



only notify the property which changed
you can get full properties by getRoomProperties() function  




##### [getRoomStateStream](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/getRoomStateStream.md)() ValueNotifier&lt;[ZegoUIKitRoomState](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitRoomState-class.md)>



get room state notifier  




##### [joinRoom](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/joinRoom.md)(String roomID, {String token = '', bool markAsLargeRoom = false}) Future&lt;[ZegoRoomLoginResult](../zego_uikit_prebuilt_live_audio_room/ZegoRoomLoginResult-class.md)>



join room  




##### [leaveRoom](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/leaveRoom.md)() Future&lt;[ZegoRoomLogoutResult](../zego_uikit_prebuilt_live_audio_room/ZegoRoomLogoutResult-class.md)>



leave room  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [setRoomProperty](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/setRoomProperty.md)(String key, String value) Future&lt;bool>



update one room property  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [updateRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/updateRoomProperties.md)(Map&lt;String, String> properties) Future&lt;bool>



update room properties  






## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoRoomService/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















