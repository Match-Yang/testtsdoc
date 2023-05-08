


# ZegoUserService mixin















**Mixin Applications**

- [ZegoUIKit](../zego_uikit_prebuilt_live_audio_room/ZegoUIKit-class.md)



## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [getAllUsers](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getAllUsers.md)() List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>



get all users, include local user and remote users  




##### [getInRoomUserAttributesNotifier](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getInRoomUserAttributesNotifier.md)(String userID) ValueNotifier&lt;ZegoUIKitUserAttributes>



get notifier of in-room user attributes  




##### [getLocalUser](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getLocalUser.md)() [ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)



get local user  




##### [getMeRemovedFromRoomStream](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getMeRemovedFromRoomStream.md)() Stream&lt;String>



get kicked out notifier  




##### [getRemoteUsers](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getRemoteUsers.md)() List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>



get remote users, not include local user  




##### [getUser](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getUser.md)(String userID) [ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)



get user by user id  




##### [getUserJoinStream](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getUserJoinStream.md)() Stream&lt;List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>>



get user join notifier  




##### [getUserLeaveStream](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getUserLeaveStream.md)() Stream&lt;List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>>



get user leave notifier  




##### [getUserListStream](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/getUserListStream.md)() Stream&lt;List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)>>



get user list notifier  




##### [login](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/login.md)(String id, String name) void



login  




##### [logout](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/logout.md)() void



logout  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [removeUserFromRoom](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/removeUserFromRoom.md)(List&lt;String> userIDs) Future&lt;bool>



remove user from room, kick out  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoUserService/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















