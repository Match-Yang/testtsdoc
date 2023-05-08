


# ZegoSignalingPluginRoomAPI mixin















**Mixin Applications**

- [ZegoSignalingPluginInterface](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInterface-class.md)
- [ZegoSignalingPluginRoomAPIImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl-class.md)



## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [beginRoomPropertiesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/beginRoomPropertiesBatchOperation.md)({required String roomID, required bool isForce, required bool isDeleteAfterOwnerLeft, required bool isUpdateOwner}) void



begin room properties batch operation  




##### [deleteRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/deleteRoomProperties.md)({required String roomID, required List&lt;String> keys, required bool isForce}) Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)>



delete room properties  




##### [endRoomPropertiesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/endRoomPropertiesBatchOperation.md)({required String roomID}) Future&lt;[ZegoSignalingPluginEndRoomBatchOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEndRoomBatchOperationResult-class.md)>



end room properties batch operation  




##### [joinRoom](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/joinRoom.md)({required String roomID, required String roomName, Map&lt;String, String> roomAttributes = const {}, int roomDestroyDelayTime = 0}) Future&lt;[ZegoSignalingPluginJoinRoomResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginJoinRoomResult-class.md)>



join room  




##### [leaveRoom](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/leaveRoom.md)({required String roomID}) Future&lt;[ZegoSignalingPluginLeaveRoomResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginLeaveRoomResult-class.md)>



leave room  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [queryRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/queryRoomProperties.md)({required String roomID}) Future&lt;[ZegoSignalingPluginQueryRoomPropertiesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryRoomPropertiesResult-class.md)>



query room properties  




##### [queryUsersInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/queryUsersInRoomAttributes.md)({required String roomID, int count = 100, String nextFlag = ''}) Future&lt;[ZegoSignalingPluginQueryUsersInRoomAttributesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryUsersInRoomAttributesResult-class.md)>



query users in room attributes  




##### [setUsersInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/setUsersInRoomAttributes.md)({required String roomID, required List&lt;String> userIDs, required Map&lt;String, String> setAttributes, bool isDeleteAfterOwnerLeft = true}) Future&lt;[ZegoSignalingPluginSetUsersInRoomAttributesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetUsersInRoomAttributesResult-class.md)>



set users in room attributes  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [updateRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/updateRoomProperties.md)({required String roomID, required bool isForce, required bool isDeleteAfterOwnerLeft, required bool isUpdateOwner, required Map&lt;String, String> roomProperties}) Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)>



update room properties  






## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















