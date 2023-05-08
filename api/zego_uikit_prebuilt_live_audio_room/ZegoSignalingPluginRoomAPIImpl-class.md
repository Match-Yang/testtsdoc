


# ZegoSignalingPluginRoomAPIImpl class













**Implemented types**

- [ZegoSignalingPluginRoomAPI](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI-mixin.md)


**Implementers**

- [ZegoUIKitSignalingPlugin](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin-class.md)





## Constructors

[ZegoSignalingPluginRoomAPIImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/ZegoSignalingPluginRoomAPIImpl.md) ()

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [beginRoomPropertiesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/beginRoomPropertiesBatchOperation.md)({required String roomID, bool isForce = false, bool isDeleteAfterOwnerLeft = false, bool isUpdateOwner = false}) void



begin room properties batch operation  
_<span class="feature">override</span>_



##### [deleteRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/deleteRoomProperties.md)({required String roomID, required List&lt;String> keys, required bool isForce}) Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)>



delete room properties  
_<span class="feature">override</span>_



##### [endRoomPropertiesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/endRoomPropertiesBatchOperation.md)({required String roomID}) Future&lt;[ZegoSignalingPluginEndRoomBatchOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEndRoomBatchOperationResult-class.md)>



end room properties batch operation  
_<span class="feature">override</span>_



##### [joinRoom](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/joinRoom.md)({required String roomID, required String roomName, Map&lt;String, String> roomAttributes = const {}, int roomDestroyDelayTime = 0}) Future&lt;[ZegoSignalingPluginJoinRoomResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginJoinRoomResult-class.md)>



join room  
_<span class="feature">override</span>_



##### [leaveRoom](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/leaveRoom.md)({required String roomID}) Future&lt;[ZegoSignalingPluginLeaveRoomResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginLeaveRoomResult-class.md)>



leave room  
_<span class="feature">override</span>_



##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [queryRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/queryRoomProperties.md)({required String roomID}) Future&lt;[ZegoSignalingPluginQueryRoomPropertiesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryRoomPropertiesResult-class.md)>



query room properties  
_<span class="feature">override</span>_



##### [queryUsersInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/queryUsersInRoomAttributes.md)({required String roomID, int count = 100, String nextFlag = ''}) Future&lt;[ZegoSignalingPluginQueryUsersInRoomAttributesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryUsersInRoomAttributesResult-class.md)>



query users in room attributes  
_<span class="feature">override</span>_



##### [setUsersInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/setUsersInRoomAttributes.md)({required String roomID, required List&lt;String> userIDs, required Map&lt;String, String> setAttributes, bool isDeleteAfterOwnerLeft = true}) Future&lt;[ZegoSignalingPluginSetUsersInRoomAttributesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetUsersInRoomAttributesResult-class.md)>



set users in room attributes  
_<span class="feature">override</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [updateRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/updateRoomProperties.md)({required String roomID, required Map&lt;String, String> roomProperties, bool isForce = false, bool isDeleteAfterOwnerLeft = false, bool isUpdateOwner = false}) Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)>



update room properties  
_<span class="feature">override</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















