


# ZegoUIKitSignalingPlugin class













**Implemented types**

- [ZegoSignalingPluginInterface](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInterface-class.md)

**Mixed in types**

- [ZegoSignalingPluginRoomAPIImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl-class.md)
- [ZegoSignalingPluginRoomEventImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEventImpl-class.md)
- [ZegoSignalingPluginInvitationAPIImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationAPIImpl-class.md)
- [ZegoSignalingPluginInvitationEventImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEventImpl-class.md)
- [ZegoSignalingPluginUserAPIImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserAPIImpl-class.md)
- [ZegoSignalingPluginUserEventImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserEventImpl-class.md)
- [ZegoSignalingPluginNotificationAPIImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationAPIImpl-class.md)
- [ZegoSignalingPluginNotificationEventImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationEventImpl-class.md)
- [ZegoSignalingPluginMessageAPIImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginMessageAPIImpl-class.md)
- [ZegoSignalingPluginMessageEventImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginMessageEventImpl-class.md)
- [ZegoSignalingPluginBackgroundMessageAPIImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginBackgroundMessageAPIImpl-class.md)
- [ZegoSignalingPluginBackgroundMessageEventImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginBackgroundMessageEventImpl-class.md)
- [ZegoSignalingPluginCallKitAPIImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitAPIImpl-class.md)
- [ZegoSignalingPluginCallKitEventImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl-class.md)
- [IZegoUIKitPlugin](../zego_uikit_prebuilt_live_audio_room/IZegoUIKitPlugin-mixin.md)






## Constructors

[ZegoUIKitSignalingPlugin](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin/ZegoUIKitSignalingPlugin.md) ()

   _factory_


## Properties

##### [eventCenter](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin/eventCenter.md) &#8594; ZegoSignalingPluginEventCenter



  
_<span class="feature">read-only</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [acceptInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationAPIImpl/acceptInvitation.md)({required String invitationID, String extendedData = ''}) Future&lt;[ZegoSignalingPluginResponseInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [activeAudioByCallKit](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitAPIImpl/activeAudioByCallKit.md)() void



  
_<span class="feature">inherited</span>_



##### [beginRoomPropertiesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/beginRoomPropertiesBatchOperation.md)({required String roomID, bool isForce = false, bool isDeleteAfterOwnerLeft = false, bool isUpdateOwner = false}) void



begin room properties batch operation  
_<span class="feature">inherited</span>_



##### [cancelInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationAPIImpl/cancelInvitation.md)({required String invitationID, required List&lt;String> invitees, String extendedData = ''}) Future&lt;[ZegoSignalingPluginCancelInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCancelInvitationResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [connectUser](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserAPIImpl/connectUser.md)({required String id, String name = ''}) Future&lt;[ZegoSignalingPluginConnectUserResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginConnectUserResult-class.md)>



login  
_<span class="feature">inherited</span>_



##### [deleteRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/deleteRoomProperties.md)({required String roomID, required List&lt;String> keys, required bool isForce}) Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)>



delete room properties  
_<span class="feature">inherited</span>_



##### [disconnectUser](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserAPIImpl/disconnectUser.md)([Duration timeout = const Duration(seconds: 2)]) Future&lt;[ZegoSignalingPluginDisconnectUserResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginDisconnectUserResult-class.md)>



logout  
_<span class="feature">inherited</span>_



##### [enableNotifyWhenAppRunningInBackgroundOrQuit](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationAPIImpl/enableNotifyWhenAppRunningInBackgroundOrQuit.md)({bool isIOSSandboxEnvironment = false, bool enableIOSVoIP = true, String appName = ''}) Future&lt;[ZegoSignalingPluginEnableNotifyResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEnableNotifyResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [endRoomPropertiesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/endRoomPropertiesBatchOperation.md)({required String roomID}) Future&lt;[ZegoSignalingPluginEndRoomBatchOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEndRoomBatchOperationResult-class.md)>



end room properties batch operation  
_<span class="feature">inherited</span>_



##### [getBackgroundThroughMessageReceivedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginBackgroundMessageEventImpl/getBackgroundThroughMessageReceivedEventStream.md)() Stream&lt;[ZegoSignalingPluginThroughMessageReceivedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginThroughMessageReceivedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitActivateAudioEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitActivateAudioEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider's audio session activation state changes.  
_<span class="feature">inherited</span>_



##### [getCallkitDeactivateAudioEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitDeactivateAudioEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformAnswerCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformAnswerCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformEndCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformEndCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformPlayDTMFCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformPlayDTMFCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformSetGroupCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformSetGroupCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformSetHeldCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformSetHeldCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformSetMutedCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformSetMutedCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitSetMutedCallActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitSetMutedCallActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformStartCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformStartCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



each perform*CallAction method is called sequentially for each action in the transaction  
_<span class="feature">inherited</span>_



##### [getCallkitProviderDidBeginEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitProviderDidBeginEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider has been fully created and is ready to send actions and receive updates  
_<span class="feature">inherited</span>_



##### [getCallkitProviderDidResetEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitProviderDidResetEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider has been reset. Delegates must respond to this callback by cleaning up all internal call state (disconnecting communication channels, releasing network resources, etc.). This callback can be treated as a request to end all calls without the need to respond to any actions  
_<span class="feature">inherited</span>_



##### [getCallkitTimedOutPerformingActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitTimedOutPerformingActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



Called when an action was not performed in time and has been inherently failed. Depending on the action, this timeout may also force the call to end. An action that has already timed out should not be fulfilled or failed by the provider delegate  
_<span class="feature">inherited</span>_



##### [getConnectionStateChangedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserEventImpl/getConnectionStateChangedEventStream.md)() Stream&lt;[ZegoSignalingPluginConnectionStateChangedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginConnectionStateChangedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getErrorEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin/getErrorEventStream.md)() Stream&lt;[ZegoSignalingPluginErrorEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginErrorEvent-class.md)>



get error event stream  
_<span class="feature">override</span>_



##### [getIncomingInvitationCancelledEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEventImpl/getIncomingInvitationCancelledEventStream.md)() Stream&lt;[ZegoSignalingPluginIncomingInvitationCancelledEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginIncomingInvitationCancelledEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getIncomingInvitationReceivedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEventImpl/getIncomingInvitationReceivedEventStream.md)() Stream&lt;[ZegoSignalingPluginIncomingInvitationReceivedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginIncomingInvitationReceivedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getIncomingInvitationTimeoutEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEventImpl/getIncomingInvitationTimeoutEventStream.md)() Stream&lt;[ZegoSignalingPluginIncomingInvitationTimeoutEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginIncomingInvitationTimeoutEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getInRoomTextMessageReceivedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginMessageEventImpl/getInRoomTextMessageReceivedEventStream.md)() Stream&lt;[ZegoSignalingPluginInRoomTextMessageReceivedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInRoomTextMessageReceivedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getNotificationArrivedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationEventImpl/getNotificationArrivedEventStream.md)() Stream&lt;[ZegoSignalingPluginNotificationArrivedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationArrivedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getNotificationClickedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationEventImpl/getNotificationClickedEventStream.md)() Stream&lt;[ZegoSignalingPluginNotificationClickedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationClickedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getNotificationRegisteredEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationEventImpl/getNotificationRegisteredEventStream.md)() Stream&lt;[ZegoSignalingPluginNotificationRegisteredEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationRegisteredEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getOutgoingInvitationAcceptedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEventImpl/getOutgoingInvitationAcceptedEventStream.md)() Stream&lt;[ZegoSignalingPluginOutgoingInvitationAcceptedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginOutgoingInvitationAcceptedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getOutgoingInvitationRejectedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEventImpl/getOutgoingInvitationRejectedEventStream.md)() Stream&lt;[ZegoSignalingPluginOutgoingInvitationRejectedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginOutgoingInvitationRejectedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getOutgoingInvitationTimeoutEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEventImpl/getOutgoingInvitationTimeoutEventStream.md)() Stream&lt;[ZegoSignalingPluginOutgoingInvitationTimeoutEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginOutgoingInvitationTimeoutEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getPluginType](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin/getPluginType.md)() [ZegoUIKitPluginType](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPluginType.md)



  
_<span class="feature">override</span>_



##### [getRoomMemberJoinedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEventImpl/getRoomMemberJoinedEventStream.md)() Stream&lt;[ZegoSignalingPluginRoomMemberJoinedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomMemberJoinedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getRoomMemberLeftEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEventImpl/getRoomMemberLeftEventStream.md)() Stream&lt;[ZegoSignalingPluginRoomMemberLeftEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomMemberLeftEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getRoomPropertiesBatchUpdatedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEventImpl/getRoomPropertiesBatchUpdatedEventStream.md)() Stream&lt;[ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getRoomPropertiesUpdatedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEventImpl/getRoomPropertiesUpdatedEventStream.md)() Stream&lt;[ZegoSignalingPluginRoomPropertiesUpdatedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesUpdatedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getRoomStateChangedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEventImpl/getRoomStateChangedEventStream.md)() Stream&lt;[ZegoSignalingPluginRoomStateChangedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomStateChangedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getTokenWillExpireEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserEventImpl/getTokenWillExpireEventStream.md)() Stream&lt;[ZegoSignalingPluginTokenWillExpireEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginTokenWillExpireEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getUsersInRoomAttributesUpdatedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEventImpl/getUsersInRoomAttributesUpdatedEventStream.md)() Stream&lt;[ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getVersion](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin/getVersion.md)() Future&lt;String>



  
_<span class="feature">override</span>_



##### [init](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin/init.md)({required int appID, String appSign = ''}) Future&lt;void>



  
_<span class="feature">override</span>_



##### [joinRoom](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/joinRoom.md)({required String roomID, required String roomName, Map&lt;String, String> roomAttributes = const {}, int roomDestroyDelayTime = 0}) Future&lt;[ZegoSignalingPluginJoinRoomResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginJoinRoomResult-class.md)>



join room  
_<span class="feature">inherited</span>_



##### [leaveRoom](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/leaveRoom.md)({required String roomID}) Future&lt;[ZegoSignalingPluginLeaveRoomResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginLeaveRoomResult-class.md)>



leave room  
_<span class="feature">inherited</span>_



##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [queryRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/queryRoomProperties.md)({required String roomID}) Future&lt;[ZegoSignalingPluginQueryRoomPropertiesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryRoomPropertiesResult-class.md)>



query room properties  
_<span class="feature">inherited</span>_



##### [queryUsersInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/queryUsersInRoomAttributes.md)({required String roomID, int count = 100, String nextFlag = ''}) Future&lt;[ZegoSignalingPluginQueryUsersInRoomAttributesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryUsersInRoomAttributesResult-class.md)>



query users in room attributes  
_<span class="feature">inherited</span>_



##### [refuseInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationAPIImpl/refuseInvitation.md)({required String invitationID, String extendedData = ''}) Future&lt;[ZegoSignalingPluginResponseInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [renewToken](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserAPIImpl/renewToken.md)(String token) Future&lt;[ZegoSignalingPluginRenewTokenResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRenewTokenResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [sendInRoomTextMessage](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginMessageAPIImpl/sendInRoomTextMessage.md)({required String roomID, required String message}) Future&lt;[ZegoSignalingPluginInRoomTextMessageResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInRoomTextMessageResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [sendInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationAPIImpl/sendInvitation.md)({required List&lt;String> invitees, required int timeout, String extendedData = '', [ZegoSignalingPluginNotificationConfig](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationConfig-class.md)? notificationConfig}) Future&lt;[ZegoSignalingPluginSendInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSendInvitationResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [setBackgroundMessageHandler](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginBackgroundMessageAPIImpl/setBackgroundMessageHandler.md)([ZegoSignalingPluginZPNsBackgroundMessageHandler](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginZPNsBackgroundMessageHandler.md) handler) Future&lt;[ZegoSignalingPluginSetBackgroundMessageHandlerResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetBackgroundMessageHandlerResult-class.md)>



only for Android  
_<span class="feature">inherited</span>_



##### [setIncomingPushReceivedHandler](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitAPIImpl/setIncomingPushReceivedHandler.md)([ZegoSignalingIncomingPushReceivedHandler](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingIncomingPushReceivedHandler.md) handler) Future&lt;void>



  
_<span class="feature">inherited</span>_



##### [setUsersInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/setUsersInRoomAttributes.md)({required String roomID, required List&lt;String> userIDs, required Map&lt;String, String> setAttributes, bool isDeleteAfterOwnerLeft = true}) Future&lt;[ZegoSignalingPluginSetUsersInRoomAttributesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetUsersInRoomAttributesResult-class.md)>



set users in room attributes  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [uninit](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin/uninit.md)() Future&lt;void>



  
_<span class="feature">override</span>_



##### [updateRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPIImpl/updateRoomProperties.md)({required String roomID, required Map&lt;String, String> roomProperties, bool isForce = false, bool isDeleteAfterOwnerLeft = false, bool isUpdateOwner = false}) Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)>



update room properties  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_





## Static Properties

##### [instance](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin/instance.md) &#8594; [ZegoUIKitSignalingPlugin](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin-class.md)



  
_<span class="feature">final</span>_













