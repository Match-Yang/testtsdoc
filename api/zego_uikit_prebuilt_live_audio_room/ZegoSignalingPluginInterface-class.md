


# ZegoSignalingPluginInterface class









<p>For all apis and events, See mixins.</p>





**Mixed in types**

- [ZegoSignalingPluginRoomAPI](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI-mixin.md)
- [ZegoSignalingPluginRoomEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEvent-mixin.md)
- [ZegoSignalingPluginInvitationAPI](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationAPI-mixin.md)
- [ZegoSignalingPluginInvitationEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEvent-mixin.md)
- [ZegoSignalingPluginUserAPI](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserAPI-mixin.md)
- [ZegoSignalingPluginUserEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserEvent-mixin.md)
- [ZegoSignalingPluginNotificationAPI](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationAPI-mixin.md)
- [ZegoSignalingPluginNotificationEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationEvent-mixin.md)
- [ZegoSignalingPluginMessageAPI](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginMessageAPI-mixin.md)
- [ZegoSignalingPluginMessageEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginMessageEvent-mixin.md)
- [ZegoSignalingPluginBackgroundMessageAPI](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginBackgroundMessageAPI-mixin.md)
- [ZegoSignalingPluginBackgroundMessageEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginBackgroundMessageEvent-mixin.md)
- [ZegoSignalingPluginCallKitAPI](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitAPI-mixin.md)
- [ZegoSignalingPluginCallKitEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent-mixin.md)
- [IZegoUIKitPlugin](../zego_uikit_prebuilt_live_audio_room/IZegoUIKitPlugin-mixin.md)

**Implementers**

- [ZegoUIKitSignalingPlugin](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin-class.md)





## Constructors

[ZegoSignalingPluginInterface](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInterface/ZegoSignalingPluginInterface.md) ()

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [acceptInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationAPI/acceptInvitation.md)({required String invitationID, String extendedData = ''}) Future&lt;[ZegoSignalingPluginResponseInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [activeAudioByCallKit](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitAPI/activeAudioByCallKit.md)() void



  
_<span class="feature">inherited</span>_



##### [beginRoomPropertiesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/beginRoomPropertiesBatchOperation.md)({required String roomID, required bool isForce, required bool isDeleteAfterOwnerLeft, required bool isUpdateOwner}) void



begin room properties batch operation  
_<span class="feature">inherited</span>_



##### [cancelInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationAPI/cancelInvitation.md)({required String invitationID, required List&lt;String> invitees, String extendedData = ''}) Future&lt;[ZegoSignalingPluginCancelInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCancelInvitationResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [connectUser](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserAPI/connectUser.md)({required String id, String name = ''}) Future&lt;[ZegoSignalingPluginConnectUserResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginConnectUserResult-class.md)>



login  
_<span class="feature">inherited</span>_



##### [deleteRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/deleteRoomProperties.md)({required String roomID, required List&lt;String> keys, required bool isForce}) Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)>



delete room properties  
_<span class="feature">inherited</span>_



##### [disconnectUser](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserAPI/disconnectUser.md)() Future&lt;[ZegoSignalingPluginDisconnectUserResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginDisconnectUserResult-class.md)>



logout  
_<span class="feature">inherited</span>_



##### [enableNotifyWhenAppRunningInBackgroundOrQuit](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationAPI/enableNotifyWhenAppRunningInBackgroundOrQuit.md)({bool isIOSSandboxEnvironment = false, bool enableIOSVoIP = true, String appName = ''}) Future&lt;[ZegoSignalingPluginEnableNotifyResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEnableNotifyResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [endRoomPropertiesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/endRoomPropertiesBatchOperation.md)({required String roomID}) Future&lt;[ZegoSignalingPluginEndRoomBatchOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEndRoomBatchOperationResult-class.md)>



end room properties batch operation  
_<span class="feature">inherited</span>_



##### [getBackgroundThroughMessageReceivedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginBackgroundMessageEvent/getBackgroundThroughMessageReceivedEventStream.md)() Stream&lt;[ZegoSignalingPluginThroughMessageReceivedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginThroughMessageReceivedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitActivateAudioEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitActivateAudioEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider's audio session activation state changes.  
_<span class="feature">inherited</span>_



##### [getCallkitDeactivateAudioEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitDeactivateAudioEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformAnswerCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformAnswerCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformEndCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformEndCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformPlayDTMFCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformPlayDTMFCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformSetGroupCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformSetGroupCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformSetHeldCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformSetHeldCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformSetMutedCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformSetMutedCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitSetMutedCallActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitSetMutedCallActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformStartCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformStartCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



each perform*CallAction method is called sequentially for each action in the transaction  
_<span class="feature">inherited</span>_



##### [getCallkitProviderDidBeginEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitProviderDidBeginEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider has been fully created and is ready to send actions and receive updates  
_<span class="feature">inherited</span>_



##### [getCallkitProviderDidResetEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitProviderDidResetEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider has been reset. Delegates must respond to this callback by cleaning up all internal call state (disconnecting communication channels, releasing network resources, etc.). This callback can be treated as a request to end all calls without the need to respond to any actions  
_<span class="feature">inherited</span>_



##### [getCallkitTimedOutPerformingActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitTimedOutPerformingActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



Called when an action was not performed in time and has been inherently failed. Depending on the action, this timeout may also force the call to end. An action that has already timed out should not be fulfilled or failed by the provider delegate  
_<span class="feature">inherited</span>_



##### [getConnectionStateChangedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserEvent/getConnectionStateChangedEventStream.md)() Stream&lt;[ZegoSignalingPluginConnectionStateChangedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginConnectionStateChangedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getErrorEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInterface/getErrorEventStream.md)() Stream&lt;[ZegoSignalingPluginErrorEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginErrorEvent-class.md)>



get error event stream  




##### [getIncomingInvitationCancelledEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEvent/getIncomingInvitationCancelledEventStream.md)() Stream&lt;[ZegoSignalingPluginIncomingInvitationCancelledEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginIncomingInvitationCancelledEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getIncomingInvitationReceivedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEvent/getIncomingInvitationReceivedEventStream.md)() Stream&lt;[ZegoSignalingPluginIncomingInvitationReceivedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginIncomingInvitationReceivedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getIncomingInvitationTimeoutEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEvent/getIncomingInvitationTimeoutEventStream.md)() Stream&lt;[ZegoSignalingPluginIncomingInvitationTimeoutEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginIncomingInvitationTimeoutEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getInRoomTextMessageReceivedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginMessageEvent/getInRoomTextMessageReceivedEventStream.md)() Stream&lt;[ZegoSignalingPluginInRoomTextMessageReceivedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInRoomTextMessageReceivedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getNotificationArrivedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationEvent/getNotificationArrivedEventStream.md)() Stream&lt;[ZegoSignalingPluginNotificationArrivedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationArrivedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getNotificationClickedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationEvent/getNotificationClickedEventStream.md)() Stream&lt;[ZegoSignalingPluginNotificationClickedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationClickedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getNotificationRegisteredEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationEvent/getNotificationRegisteredEventStream.md)() Stream&lt;[ZegoSignalingPluginNotificationRegisteredEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationRegisteredEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getOutgoingInvitationAcceptedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEvent/getOutgoingInvitationAcceptedEventStream.md)() Stream&lt;[ZegoSignalingPluginOutgoingInvitationAcceptedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginOutgoingInvitationAcceptedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getOutgoingInvitationRejectedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEvent/getOutgoingInvitationRejectedEventStream.md)() Stream&lt;[ZegoSignalingPluginOutgoingInvitationRejectedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginOutgoingInvitationRejectedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getOutgoingInvitationTimeoutEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationEvent/getOutgoingInvitationTimeoutEventStream.md)() Stream&lt;[ZegoSignalingPluginOutgoingInvitationTimeoutEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginOutgoingInvitationTimeoutEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getPluginType](../zego_uikit_prebuilt_live_audio_room/IZegoUIKitPlugin/getPluginType.md)() [ZegoUIKitPluginType](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPluginType.md)



  
_<span class="feature">inherited</span>_



##### [getRoomMemberJoinedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEvent/getRoomMemberJoinedEventStream.md)() Stream&lt;[ZegoSignalingPluginRoomMemberJoinedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomMemberJoinedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getRoomMemberLeftEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEvent/getRoomMemberLeftEventStream.md)() Stream&lt;[ZegoSignalingPluginRoomMemberLeftEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomMemberLeftEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getRoomPropertiesBatchUpdatedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEvent/getRoomPropertiesBatchUpdatedEventStream.md)() Stream&lt;[ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getRoomPropertiesUpdatedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEvent/getRoomPropertiesUpdatedEventStream.md)() Stream&lt;[ZegoSignalingPluginRoomPropertiesUpdatedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesUpdatedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getRoomStateChangedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEvent/getRoomStateChangedEventStream.md)() Stream&lt;[ZegoSignalingPluginRoomStateChangedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomStateChangedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getTokenWillExpireEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserEvent/getTokenWillExpireEventStream.md)() Stream&lt;[ZegoSignalingPluginTokenWillExpireEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginTokenWillExpireEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getUsersInRoomAttributesUpdatedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomEvent/getUsersInRoomAttributesUpdatedEventStream.md)() Stream&lt;[ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getVersion](../zego_uikit_prebuilt_live_audio_room/IZegoUIKitPlugin/getVersion.md)() Future&lt;String>



  
_<span class="feature">inherited</span>_



##### [init](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInterface/init.md)({required int appID, String appSign = ''}) Future&lt;void>



  




##### [joinRoom](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/joinRoom.md)({required String roomID, required String roomName, Map&lt;String, String> roomAttributes = const {}, int roomDestroyDelayTime = 0}) Future&lt;[ZegoSignalingPluginJoinRoomResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginJoinRoomResult-class.md)>



join room  
_<span class="feature">inherited</span>_



##### [leaveRoom](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/leaveRoom.md)({required String roomID}) Future&lt;[ZegoSignalingPluginLeaveRoomResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginLeaveRoomResult-class.md)>



leave room  
_<span class="feature">inherited</span>_



##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [queryRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/queryRoomProperties.md)({required String roomID}) Future&lt;[ZegoSignalingPluginQueryRoomPropertiesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryRoomPropertiesResult-class.md)>



query room properties  
_<span class="feature">inherited</span>_



##### [queryUsersInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/queryUsersInRoomAttributes.md)({required String roomID, int count = 100, String nextFlag = ''}) Future&lt;[ZegoSignalingPluginQueryUsersInRoomAttributesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryUsersInRoomAttributesResult-class.md)>



query users in room attributes  
_<span class="feature">inherited</span>_



##### [refuseInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationAPI/refuseInvitation.md)({required String invitationID, String extendedData = ''}) Future&lt;[ZegoSignalingPluginResponseInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [renewToken](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUserAPI/renewToken.md)(String token) Future&lt;[ZegoSignalingPluginRenewTokenResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRenewTokenResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [sendInRoomTextMessage](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginMessageAPI/sendInRoomTextMessage.md)({required String roomID, required String message}) Future&lt;[ZegoSignalingPluginInRoomTextMessageResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInRoomTextMessageResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [sendInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInvitationAPI/sendInvitation.md)({required List&lt;String> invitees, required int timeout, String extendedData = '', [ZegoSignalingPluginNotificationConfig](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginNotificationConfig-class.md)? notificationConfig}) Future&lt;[ZegoSignalingPluginSendInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSendInvitationResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [setBackgroundMessageHandler](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginBackgroundMessageAPI/setBackgroundMessageHandler.md)([ZegoSignalingPluginZPNsBackgroundMessageHandler](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginZPNsBackgroundMessageHandler.md) handler) Future&lt;[ZegoSignalingPluginSetBackgroundMessageHandlerResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetBackgroundMessageHandlerResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [setIncomingPushReceivedHandler](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitAPI/setIncomingPushReceivedHandler.md)([ZegoSignalingIncomingPushReceivedHandler](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingIncomingPushReceivedHandler.md) handler) Future&lt;void>



  
_<span class="feature">inherited</span>_



##### [setUsersInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/setUsersInRoomAttributes.md)({required String roomID, required List&lt;String> userIDs, required Map&lt;String, String> setAttributes, bool isDeleteAfterOwnerLeft = true}) Future&lt;[ZegoSignalingPluginSetUsersInRoomAttributesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetUsersInRoomAttributesResult-class.md)>



set users in room attributes  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [uninit](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInterface/uninit.md)() Future&lt;void>



  




##### [updateRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/updateRoomProperties.md)({required String roomID, required bool isForce, required bool isDeleteAfterOwnerLeft, required bool isUpdateOwner, required Map&lt;String, String> roomProperties}) Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)>



update room properties  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomAPI/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















