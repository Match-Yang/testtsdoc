


# ZegoUIKitSignalingPluginImpl class













## Constructors

[ZegoUIKitSignalingPluginImpl](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/ZegoUIKitSignalingPluginImpl.md) ()

   _factory_


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [acceptInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/acceptInvitation.md)({required String inviterID, required String data}) Future&lt;[ZegoSignalingPluginResponseInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)>



invitee accept the call invitation
<code>inviterID</code> inviter id, who send invitation
<code>data</code> extended field  
_<span class="feature">inherited</span>_



##### [activeAudioByCallKit](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/activeAudioByCallKit.md)() Future&lt;void>



Call this function when you <code>didReceiveIncomingPush</code> to active audio in callkit mode  




##### [beginRoomPropertiesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/beginRoomPropertiesBatchOperation.md)({required String roomID, bool isDeleteAfterOwnerLeft = false, bool isForce = false, bool isUpdateOwner = false}) void



begin room properties in batch operation  
_<span class="feature">inherited</span>_



##### [cancelInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/cancelInvitation.md)({required List&lt;String> invitees, required String data}) Future&lt;[ZegoSignalingPluginCancelInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCancelInvitationResult-class.md)>



cancel invitation to one or more specified users
<code>inviteeID</code> invitee's id
<code>data</code> extended field  
_<span class="feature">inherited</span>_



##### [deleteRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/deleteRoomProperties.md)({required String roomID, required List&lt;String> keys, bool isForce = false}) Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)>



delete room properties  
_<span class="feature">inherited</span>_



##### [enableNotifyWhenAppRunningInBackgroundOrQuit](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/enableNotifyWhenAppRunningInBackgroundOrQuit.md)(bool enabled, {bool isIOSSandboxEnvironment = false, bool enableIOSVoIP = true, String appName = ''}) Future&lt;[ZegoSignalingPluginEnableNotifyResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEnableNotifyResult-class.md)>



enable notification  
_<span class="feature">inherited</span>_



##### [endRoomPropertiesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/endRoomPropertiesBatchOperation.md)({required String roomID}) Future&lt;[ZegoSignalingPluginEndRoomBatchOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginEndRoomBatchOperationResult-class.md)>



end room properties in batch operation  
_<span class="feature">inherited</span>_



##### [getCallkitActivateAudioEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitActivateAudioEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider's audio session activation state changes.  
_<span class="feature">inherited</span>_



##### [getCallkitDeactivateAudioEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitDeactivateAudioEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformAnswerCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitPerformAnswerCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformEndCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitPerformEndCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformPlayDTMFCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitPerformPlayDTMFCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformSetGroupCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitPerformSetGroupCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformSetHeldCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitPerformSetHeldCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformSetMutedCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitPerformSetMutedCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitSetMutedCallActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitSetMutedCallActionEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getCallkitPerformStartCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitPerformStartCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



each perform*CallAction method is called sequentially for each action in the transaction  
_<span class="feature">inherited</span>_



##### [getCallkitProviderDidBeginEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitProviderDidBeginEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider has been fully created and is ready to send actions and receive updates  
_<span class="feature">inherited</span>_



##### [getCallkitProviderDidResetEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitProviderDidResetEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider has been reset. Delegates must respond to this callback by cleaning up all internal call state (disconnecting communication channels, releasing network resources, etc.). This callback can be treated as a request to end all calls without the need to respond to any actions  
_<span class="feature">inherited</span>_



##### [getCallkitTimedOutPerformingActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getCallkitTimedOutPerformingActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



Called when an action was not performed in time and has been inherently failed. Depending on the action, this timeout may also force the call to end. An action that has already timed out should not be fulfilled or failed by the provider delegate  
_<span class="feature">inherited</span>_



##### [getConnectionStateStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getConnectionStateStream.md)() Stream&lt;[ZegoSignalingPluginConnectionStateChangedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginConnectionStateChangedEvent-class.md)>



  




##### [getInRoomTextMessageReceivedEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getInRoomTextMessageReceivedEventStream.md)() Stream&lt;[ZegoSignalingPluginInRoomTextMessageReceivedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInRoomTextMessageReceivedEvent-class.md)>



  
_<span class="feature">inherited</span>_



##### [getInvitationAcceptedStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getInvitationAcceptedStream.md)() Stream&lt;Map&lt;String, dynamic>>



stream callback, notify when call invitation accepted by invitee  
_<span class="feature">inherited</span>_



##### [getInvitationCanceledStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getInvitationCanceledStream.md)() Stream&lt;Map&lt;String, dynamic>>



stream callback, notify when call invitation cancelled by inviter  
_<span class="feature">inherited</span>_



##### [getInvitationReceivedStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getInvitationReceivedStream.md)() Stream&lt;Map&lt;String, dynamic>>



stream callback, notify invitee when call invitation received  
_<span class="feature">inherited</span>_



##### [getInvitationRefusedStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getInvitationRefusedStream.md)() Stream&lt;Map&lt;String, dynamic>>



stream callback, notify when call invitation rejected by invitee  
_<span class="feature">inherited</span>_



##### [getInvitationResponseTimeoutStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getInvitationResponseTimeoutStream.md)() Stream&lt;Map&lt;String, dynamic>>



stream callback, When the call invitation times out, the invitee does not respond, and the inviter will receive a callback.  
_<span class="feature">inherited</span>_



##### [getInvitationTimeoutStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getInvitationTimeoutStream.md)() Stream&lt;Map&lt;String, dynamic>>



stream callback, notify invitee if invitation timeout  
_<span class="feature">inherited</span>_



##### [getRoomBatchPropertiesStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getRoomBatchPropertiesStream.md)() Stream&lt;[ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesBatchUpdatedEvent-class.md)>



get room batch properties notifier  
_<span class="feature">inherited</span>_



##### [getRoomPropertiesStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getRoomPropertiesStream.md)() Stream&lt;[ZegoSignalingPluginRoomPropertiesUpdatedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesUpdatedEvent-class.md)>



get room properties notifier  
_<span class="feature">inherited</span>_



##### [getRoomStateStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getRoomStateStream.md)() Stream&lt;[ZegoSignalingPluginRoomStateChangedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomStateChangedEvent-class.md)>



  




##### [getUsersInRoomAttributesStream](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/getUsersInRoomAttributesStream.md)() Stream&lt;[ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginUsersInRoomAttributesUpdatedEvent-class.md)>



get users in-room attributes notifier  
_<span class="feature">inherited</span>_



##### [init](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/init.md)(int appID, {String appSign = ''}) Future&lt;void>



init  




##### [initUserInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/initUserInRoomAttributes.md)() void



  
_<span class="feature">inherited</span>_



##### [joinRoom](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/joinRoom.md)(String roomID, {String roomName = ''}) Future&lt;[ZegoSignalingPluginJoinRoomResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginJoinRoomResult-class.md)>



join room  




##### [leaveRoom](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/leaveRoom.md)() Future&lt;void>



leave room  




##### [login](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/login.md)({required String id, required String name}) Future&lt;bool>



login  




##### [logout](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/logout.md)() Future&lt;void>



logout  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [queryRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/queryRoomProperties.md)({required String roomID}) Future&lt;[ZegoSignalingPluginQueryRoomPropertiesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryRoomPropertiesResult-class.md)>



query room properties  
_<span class="feature">inherited</span>_



##### [queryUsersInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/queryUsersInRoomAttributes.md)({required String roomID, String nextFlag = '', int count = 100}) Future&lt;[ZegoSignalingPluginQueryUsersInRoomAttributesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginQueryUsersInRoomAttributesResult-class.md)>



query user in-room attributes  
_<span class="feature">inherited</span>_



##### [refuseInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/refuseInvitation.md)({required String inviterID, required String data}) Future&lt;[ZegoSignalingPluginResponseInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)>



invitee reject the call invitation
<code>inviterID</code> inviter id, who send invitation
<code>data</code> extended field, you can include your reasons such as Declined  
_<span class="feature">inherited</span>_



##### [refuseInvitationByInvitationID](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/refuseInvitationByInvitationID.md)({required String invitationID, required String data}) Future&lt;[ZegoSignalingPluginResponseInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginResponseInvitationResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [sendInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/sendInvitation.md)({required String inviterName, required List&lt;String> invitees, required int timeout, required int type, required String data, [ZegoNotificationConfig](../zego_uikit_prebuilt_live_audio_room/ZegoNotificationConfig-class.md)? zegoNotificationConfig}) Future&lt;[ZegoSignalingPluginSendInvitationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSendInvitationResult-class.md)>



send invitation to one or more specified users
<code>invitees</code> list of invitees.
<code>timeout</code> timeout of the call invitation, the unit is seconds
<code>type</code> call type
<code>data</code> extended field, through which the inviter can carry information to the invitee.  
_<span class="feature">inherited</span>_



##### [setBackgroundMessageHandler](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/setBackgroundMessageHandler.md)([ZegoSignalingPluginZPNsBackgroundMessageHandler](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginZPNsBackgroundMessageHandler.md) handler) Future&lt;[ZegoSignalingPluginSetBackgroundMessageHandlerResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetBackgroundMessageHandlerResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [setIncomingPushReceivedHandler](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/setIncomingPushReceivedHandler.md)([ZegoSignalingIncomingPushReceivedHandler](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingIncomingPushReceivedHandler.md) handler) Future&lt;void>



  
_<span class="feature">inherited</span>_



##### [setUsersInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/setUsersInRoomAttributes.md)({required String roomID, required String key, required String value, required List&lt;String> userIDs}) Future&lt;[ZegoSignalingPluginSetUsersInRoomAttributesResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginSetUsersInRoomAttributesResult-class.md)>



set users in-room attributes  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [uninit](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/uninit.md)() Future&lt;void>



uninit  




##### [uninitUserInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/uninitUserInRoomAttributes.md)() void



  
_<span class="feature">inherited</span>_



##### [updateRoomProperties](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/updateRoomProperties.md)({required String roomID, required Map&lt;String, String> roomProperties, bool isForce = false, bool isDeleteAfterOwnerLeft = false, bool isUpdateOwner = false}) Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)>



  
_<span class="feature">inherited</span>_



##### [updateRoomProperty](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/updateRoomProperty.md)({required String roomID, required String key, required String value, bool isForce = false, bool isDeleteAfterOwnerLeft = false, bool isUpdateOwner = false}) Future&lt;[ZegoSignalingPluginRoomPropertiesOperationResult](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginRoomPropertiesOperationResult-class.md)>



update room property  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_





## Static Properties

##### [shared](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl/shared.md) &#8594; [ZegoUIKitSignalingPluginImpl](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPluginImpl-class.md)



  
_<span class="feature">final</span>_













