


# ZIM class













## Constructors

[ZIM](../zego_uikit_prebuilt_live_audio_room/ZIM/ZIM.md) ()

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZIM/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZIM/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [beginRoomAttributesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZIM/beginRoomAttributesBatchOperation.md)(String roomID, [ZIMRoomAttributesBatchOperationConfig](../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesBatchOperationConfig-class.md) config) void



Open combination room attribute operation.  




##### [callAccept](../zego_uikit_prebuilt_live_audio_room/ZIM/callAccept.md)(String callID, [ZIMCallAcceptConfig](../zego_uikit_prebuilt_live_audio_room/ZIMCallAcceptConfig-class.md) config) Future&lt;[ZIMCallAcceptanceSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMCallAcceptanceSentResult-class.md)>



Supported versions: 2.1.5 and above.  




##### [callCancel](../zego_uikit_prebuilt_live_audio_room/ZIM/callCancel.md)(List&lt;String> invitees, String callID, [ZIMCallCancelConfig](../zego_uikit_prebuilt_live_audio_room/ZIMCallCancelConfig-class.md) config) Future&lt;[ZIMCallCancelSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMCallCancelSentResult-class.md)>



Supported versions: 2.1.5 and above.  




##### [callInvite](../zego_uikit_prebuilt_live_audio_room/ZIM/callInvite.md)(List&lt;String> invitees, [ZIMCallInviteConfig](../zego_uikit_prebuilt_live_audio_room/ZIMCallInviteConfig-class.md) config) Future&lt;[ZIMCallInvitationSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMCallInvitationSentResult-class.md)>



Supported versions: 2.1.5 and above.  




##### [callReject](../zego_uikit_prebuilt_live_audio_room/ZIM/callReject.md)(String callID, [ZIMCallRejectConfig](../zego_uikit_prebuilt_live_audio_room/ZIMCallRejectConfig-class.md) config) Future&lt;[ZIMCallRejectionSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMCallRejectionSentResult-class.md)>



Supported versions: 2.1.5 and above.  




##### [clearConversationUnreadMessageCount](../zego_uikit_prebuilt_live_audio_room/ZIM/clearConversationUnreadMessageCount.md)(String conversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType) Future&lt;[ZIMConversationUnreadMessageCountClearedResult](../zego_uikit_prebuilt_live_audio_room/ZIMConversationUnreadMessageCountClearedResult-class.md)>



Available since: 2.1.5 and above.  




##### [createGroup](../zego_uikit_prebuilt_live_audio_room/ZIM/createGroup.md)([ZIMGroupInfo](../zego_uikit_prebuilt_live_audio_room/ZIMGroupInfo-class.md) groupInfo, List&lt;String> userIDs, [[ZIMGroupAdvancedConfig](../zego_uikit_prebuilt_live_audio_room/ZIMGroupAdvancedConfig-class.md)? config]) Future&lt;[ZIMGroupCreatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupCreatedResult-class.md)>



Available since: 2.1.5 and above.  




##### [createRoom](../zego_uikit_prebuilt_live_audio_room/ZIM/createRoom.md)([ZIMRoomInfo](../zego_uikit_prebuilt_live_audio_room/ZIMRoomInfo-class.md) roomInfo, [[ZIMRoomAdvancedConfig](../zego_uikit_prebuilt_live_audio_room/ZIMRoomAdvancedConfig-class.md)? config]) Future&lt;[ZIMRoomCreatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomCreatedResult-class.md)>



Create a room.  




##### [deleteAllMessage](../zego_uikit_prebuilt_live_audio_room/ZIM/deleteAllMessage.md)(String conversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMMessageDeleteConfig](../zego_uikit_prebuilt_live_audio_room/ZIMMessageDeleteConfig-class.md) config) Future&lt;[ZIMMessageDeletedResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageDeletedResult-class.md)>



Supported versions: 2.1.5 and above.  




##### [deleteConversation](../zego_uikit_prebuilt_live_audio_room/ZIM/deleteConversation.md)(String conversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMConversationDeleteConfig](../zego_uikit_prebuilt_live_audio_room/ZIMConversationDeleteConfig-class.md) config) Future&lt;[ZIMConversationDeletedResult](../zego_uikit_prebuilt_live_audio_room/ZIMConversationDeletedResult-class.md)>



Available since: 2.1.5 and above.  




##### [deleteGroupAttributes](../zego_uikit_prebuilt_live_audio_room/ZIM/deleteGroupAttributes.md)(List&lt;String> keys, String groupID) Future&lt;[ZIMGroupAttributesOperatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupAttributesOperatedResult-class.md)>



Available since: 2.0.0 and above.  




##### [deleteMessages](../zego_uikit_prebuilt_live_audio_room/ZIM/deleteMessages.md)(List&lt;[ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md)> messageList, String conversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMMessageDeleteConfig](../zego_uikit_prebuilt_live_audio_room/ZIMMessageDeleteConfig-class.md) config) Future&lt;[ZIMMessageDeletedResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageDeletedResult-class.md)>



Supported versions: 2.1.5 and above.
Detail description: This method implements the function of deleting messages.
Business scenario: The user needs to delete a message. When the user does not need to display a message, this method can be used to delete it.
Call timing/Notification timing: Called when the message needs to be deleted.
Note: The impact of deleting messages is limited to this account.
Restrictions: Effective after login, invalid after logout.
Scope of influence: If the deleted message is the latest message of the session, the <code>ZIMEventHandler..onConversationChanged</code> callback will be triggered, and if the message is unread, the <code>ZIMEventHandler.onConversationTotalUnreadMessageCountUpdated</code> callback will be triggered.  




##### [deleteRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZIM/deleteRoomAttributes.md)(List&lt;String> keys, String roomID, [ZIMRoomAttributesDeleteConfig](../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesDeleteConfig-class.md) config) Future&lt;[ZIMRoomAttributesOperatedCallResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesOperatedCallResult-class.md)>



Delete room attributes.  




##### [destroy](../zego_uikit_prebuilt_live_audio_room/ZIM/destroy.md)() dynamic



Destroy the ZIM instance.  




##### [dismissGroup](../zego_uikit_prebuilt_live_audio_room/ZIM/dismissGroup.md)(String groupID) Future&lt;[ZIMGroupDismissedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupDismissedResult-class.md)>



Available since: 2.1.5 and above.  




##### [downloadMediaFile](../zego_uikit_prebuilt_live_audio_room/ZIM/downloadMediaFile.md)([ZIMMediaMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMediaMessage-class.md) message, [ZIMMediaFileType](../zego_uikit_prebuilt_live_audio_room/ZIMMediaFileType.md) fileType, [ZIMMediaDownloadingProgress](../zego_uikit_prebuilt_live_audio_room/ZIMMediaDownloadingProgress.md)? progress) Future&lt;[ZIMMediaDownloadedResult](../zego_uikit_prebuilt_live_audio_room/ZIMMediaDownloadedResult-class.md)>



Download media message content.  




##### [endRoomAttributesBatchOperation](../zego_uikit_prebuilt_live_audio_room/ZIM/endRoomAttributesBatchOperation.md)(String roomID) Future&lt;[ZIMRoomAttributesBatchOperatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesBatchOperatedResult-class.md)>



Complete the property operation of the combined room.  




##### [enterRoom](../zego_uikit_prebuilt_live_audio_room/ZIM/enterRoom.md)([ZIMRoomInfo](../zego_uikit_prebuilt_live_audio_room/ZIMRoomInfo-class.md) roomInfo, [ZIMRoomAdvancedConfig](../zego_uikit_prebuilt_live_audio_room/ZIMRoomAdvancedConfig-class.md) config) Future&lt;[ZIMRoomEnteredResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomEnteredResult-class.md)>



Supported version: 2.1.5.  




##### [insertMessageToLocalDB](../zego_uikit_prebuilt_live_audio_room/ZIM/insertMessageToLocalDB.md)([ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String conversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, String senderUserID) Future&lt;[ZIMMessageInsertedResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageInsertedResult-class.md)>



Supported Versions: 2.4.0 and above.  




##### [inviteUsersIntoGroup](../zego_uikit_prebuilt_live_audio_room/ZIM/inviteUsersIntoGroup.md)(List&lt;String> userIDs, String groupID) Future&lt;[ZIMGroupUsersInvitedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupUsersInvitedResult-class.md)>



Available since: 2.1.5 and above.  




##### [joinGroup](../zego_uikit_prebuilt_live_audio_room/ZIM/joinGroup.md)(String groupID) Future&lt;[ZIMGroupJoinedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupJoinedResult-class.md)>



Available since: 2.1.5 and above.  




##### [joinRoom](../zego_uikit_prebuilt_live_audio_room/ZIM/joinRoom.md)(String roomID) Future&lt;[ZIMRoomJoinedResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomJoinedResult-class.md)>



Join a room.  




##### [kickGroupMembers](../zego_uikit_prebuilt_live_audio_room/ZIM/kickGroupMembers.md)(List&lt;String> userIDs, String groupID) Future&lt;[ZIMGroupMemberKickedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberKickedResult-class.md)>



Available since: 2.1.5 and above.  




##### [leaveGroup](../zego_uikit_prebuilt_live_audio_room/ZIM/leaveGroup.md)(String groupID) Future&lt;[ZIMGroupLeftResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupLeftResult-class.md)>



Available since: 2.1.5 and above.  




##### [leaveRoom](../zego_uikit_prebuilt_live_audio_room/ZIM/leaveRoom.md)(String roomID) Future&lt;[ZIMRoomLeftResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomLeftResult-class.md)>



Leave a room.  




##### [login](../zego_uikit_prebuilt_live_audio_room/ZIM/login.md)([ZIMUserInfo](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo-class.md) userInfo, [String? token]) Future&lt;void>



Login, you must log in before using all functions.
<code>userInfo</code> Unique ID used to identify the user. Note that the userID must be unique under the same appID, otherwise mutual kicks out will occur.
<code>token</code> The token issued by the developer's business server, used to ensure security. The generation rules are detailed in ZEGO document website.  




##### [logout](../zego_uikit_prebuilt_live_audio_room/ZIM/logout.md)() dynamic



Log out of ZIM service.  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZIM/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [queryConversationList](../zego_uikit_prebuilt_live_audio_room/ZIM/queryConversationList.md)([ZIMConversationQueryConfig](../zego_uikit_prebuilt_live_audio_room/ZIMConversationQueryConfig-class.md) config) Future&lt;[ZIMConversationListQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMConversationListQueriedResult-class.md)>



Available since: 2.1.5 and above.
Description: This method displays the session list of the logged in user.
Use cases: This interface can be invoked to get the data source when you need to display an existing message session after logging in.  




##### [queryGroupAllAttributes](../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupAllAttributes.md)(String groupID) Future&lt;[ZIMGroupAttributesQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupAttributesQueriedResult-class.md)>



Available since: 2.1.5 and above.  




##### [queryGroupAttributes](../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupAttributes.md)(List&lt;String> keys, String groupID) Future&lt;[ZIMGroupAttributesQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupAttributesQueriedResult-class.md)>



Available since: 2.1.5 and above.  




##### [queryGroupInfo](../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupInfo.md)(String groupID) Future&lt;[ZIMGroupInfoQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupInfoQueriedResult-class.md)>



Available since: 2.1.5 and above.  




##### [queryGroupList](../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupList.md)() Future&lt;[ZIMGroupListQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupListQueriedResult-class.md)>



Available since: 2.1.5 and above.  




##### [queryGroupMemberCount](../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupMemberCount.md)(String groupID) Future&lt;[ZIMGroupMemberCountQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberCountQueriedResult-class.md)>



  




##### [queryGroupMemberInfo](../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupMemberInfo.md)(String userID, String groupID) Future&lt;[ZIMGroupMemberInfoQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberInfoQueriedResult-class.md)>



Available since: 2.1.5 and above.  




##### [queryGroupMemberList](../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupMemberList.md)(String groupID, [ZIMGroupMemberQueryConfig](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberQueryConfig-class.md) config) Future&lt;[ZIMGroupMemberListQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberListQueriedResult-class.md)>



Available since: 2.1.5 and above.  




##### [queryGroupMessageReceiptReadMemberList](../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupMessageReceiptReadMemberList.md)([ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String groupID, [ZIMGroupMessageReceiptMemberQueryConfig](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMessageReceiptMemberQueryConfig-class.md) config) Future&lt;[ZIMGroupMessageReceiptMemberListQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMessageReceiptMemberListQueriedResult-class.md)>



Available since: 2.5.0 and above.  




##### [queryGroupMessageReceiptUnreadMemberList](../zego_uikit_prebuilt_live_audio_room/ZIM/queryGroupMessageReceiptUnreadMemberList.md)([ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String groupID, [ZIMGroupMessageReceiptMemberQueryConfig](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMessageReceiptMemberQueryConfig-class.md) config) Future&lt;[ZIMGroupMessageReceiptMemberListQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMessageReceiptMemberListQueriedResult-class.md)>



Available since: 2.5.0 and above.  




##### [queryHistoryMessage](../zego_uikit_prebuilt_live_audio_room/ZIM/queryHistoryMessage.md)(String conversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMMessageQueryConfig](../zego_uikit_prebuilt_live_audio_room/ZIMMessageQueryConfig-class.md) config) Future&lt;[ZIMMessageQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageQueriedResult-class.md)>



Supported versions: 2.1.5 and above.
Detailed description: This method is used to query historical messages.
Business scenario: When you need to obtain past historical messages, you can call this interface to query historical messages by paging.
Call timing/Notification timing: Called when historical messages need to be queried.
Restrictions: Effective after login, invalid after logout.  




##### [queryMessageReceiptsInfo](../zego_uikit_prebuilt_live_audio_room/ZIM/queryMessageReceiptsInfo.md)(List&lt;[ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md)> messageList, String conversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType) Future&lt;[ZIMMessageReceiptsInfoQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageReceiptsInfoQueriedResult-class.md)>



Available since: 2.5.0 and above.  




##### [queryRoomAllAttributes](../zego_uikit_prebuilt_live_audio_room/ZIM/queryRoomAllAttributes.md)(String roomID) Future&lt;[ZIMRoomAttributesQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesQueriedResult-class.md)>



Query all properties of the room.  




##### [queryRoomMemberAttributesList](../zego_uikit_prebuilt_live_audio_room/ZIM/queryRoomMemberAttributesList.md)(String roomID, [ZIMRoomMemberAttributesQueryConfig](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberAttributesQueryConfig-class.md) config) Future&lt;[ZIMRoomMemberAttributesListQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberAttributesListQueriedResult-class.md)>



Available since:2.4.0 or later.  




##### [queryRoomMemberList](../zego_uikit_prebuilt_live_audio_room/ZIM/queryRoomMemberList.md)(String roomID, [ZIMRoomMemberQueryConfig](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueryConfig-class.md) config) Future&lt;[ZIMRoomMemberQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult-class.md)>



Query the list of members in the room.  




##### [queryRoomMembersAttributes](../zego_uikit_prebuilt_live_audio_room/ZIM/queryRoomMembersAttributes.md)(List&lt;String> userIDs, String roomID) Future&lt;[ZIMRoomMembersAttributesQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMembersAttributesQueriedResult-class.md)>



Available since:2.4.0 or later.  




##### [queryRoomOnlineMemberCount](../zego_uikit_prebuilt_live_audio_room/ZIM/queryRoomOnlineMemberCount.md)(String roomID) Future&lt;[ZIMRoomOnlineMemberCountQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomOnlineMemberCountQueriedResult-class.md)>



Query the number of online members in the room.  




##### [queryUsersInfo](../zego_uikit_prebuilt_live_audio_room/ZIM/queryUsersInfo.md)(List&lt;String> userIDs, [ZIMUserInfoQueryConfig](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfoQueryConfig-class.md) config) Future&lt;[ZIMUsersInfoQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult-class.md)>



Available since: 2.1.5 and above.  




##### [renewToken](../zego_uikit_prebuilt_live_audio_room/ZIM/renewToken.md)(String token) Future&lt;[ZIMTokenRenewedResult](../zego_uikit_prebuilt_live_audio_room/ZIMTokenRenewedResult-class.md)>



Update the authentication token.  




##### [revokeMessage](../zego_uikit_prebuilt_live_audio_room/ZIM/revokeMessage.md)([ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, [ZIMMessageRevokeConfig](../zego_uikit_prebuilt_live_audio_room/ZIMMessageRevokeConfig-class.md) config) Future&lt;[ZIMMessageRevokedResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageRevokedResult-class.md)>



Available sinces: 2.5.0 and above.  




##### [sendConversationMessageReceiptRead](../zego_uikit_prebuilt_live_audio_room/ZIM/sendConversationMessageReceiptRead.md)(String conversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType) Future&lt;[ZIMConversationMessageReceiptReadSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMConversationMessageReceiptReadSentResult-class.md)>



Available since: 2.5.0 and above.  




##### [sendGroupMessage](../zego_uikit_prebuilt_live_audio_room/ZIM/sendGroupMessage.md)([ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String toGroupID, [ZIMMessageSendConfig](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendConfig-class.md) config) Future&lt;[ZIMMessageSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult-class.md)>



deprecated: This API has been deprecated since 2.4.0, please use <a href="../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessage.md">sendMessage</a> instead.  




##### [sendMediaMessage](../zego_uikit_prebuilt_live_audio_room/ZIM/sendMediaMessage.md)([ZIMMediaMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMediaMessage-class.md) message, String toConversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMMessageSendConfig](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendConfig-class.md) config, [ZIMMediaMessageSendNotification](../zego_uikit_prebuilt_live_audio_room/ZIMMediaMessageSendNotification-class.md)? notification) Future&lt;[ZIMMessageSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult-class.md)>



Send media messages.
Supported versions: 2.1.5 and above.  




##### [sendMessage](../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessage.md)([ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String toConversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType, [ZIMMessageSendConfig](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendConfig-class.md) config, [[ZIMMessageSendNotification](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendNotification-class.md)? notification]) Future&lt;[ZIMMessageSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult-class.md)>



Supported versions: 2.4.0 and above.  




##### [sendMessageReceiptsRead](../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessageReceiptsRead.md)(List&lt;[ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md)> messageList, String conversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType) Future&lt;[ZIMMessageReceiptsReadSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageReceiptsReadSentResult-class.md)>



Available since: 2.5.0 and above.
Description: This method can set the receipt of a batch of messages to become read.
Use cases: Developers can use this method to set a batch of messages with receipts that have been read. If the sender is online, it will receive the <code>onMessageReceiptChanged</code> callback.
When to call: Callable after login. It is recommended to set the settings for the messages that need to be read on the message list page. It is not recommended to mix with <a href="../zego_uikit_prebuilt_live_audio_room/ZIM/sendConversationMessageReceiptRead.md">sendConversationMessageReceiptRead</a>.
Restrictions: Only support the settings for received messages with receipt status as PROCESSING.
Related callbacks: <code>ZIMMessageReceiptsReadSentResult</code>.
Related APIs: <a href="../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessage.md">sendMessage</a>.  




##### [sendPeerMessage](../zego_uikit_prebuilt_live_audio_room/ZIM/sendPeerMessage.md)([ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String toUserID, [ZIMMessageSendConfig](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendConfig-class.md) config) Future&lt;[ZIMMessageSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult-class.md)>



deprecated: This API has been deprecated since 2.4.0, please use <a href="../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessage.md">sendMessage</a> instead.  




##### [sendRoomMessage](../zego_uikit_prebuilt_live_audio_room/ZIM/sendRoomMessage.md)([ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message, String toRoomID, [ZIMMessageSendConfig](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSendConfig-class.md) config) Future&lt;[ZIMMessageSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult-class.md)>



deprecated: This API has been deprecated since 2.4.0, please use <a href="../zego_uikit_prebuilt_live_audio_room/ZIM/sendMessage.md">sendMessage</a> instead.  




##### [setConversationNotificationStatus](../zego_uikit_prebuilt_live_audio_room/ZIM/setConversationNotificationStatus.md)([ZIMConversationNotificationStatus](../zego_uikit_prebuilt_live_audio_room/ZIMConversationNotificationStatus.md) status, String conversationID, [ZIMConversationType](../zego_uikit_prebuilt_live_audio_room/ZIMConversationType.md) conversationType) Future&lt;[ZIMConversationNotificationStatusSetResult](../zego_uikit_prebuilt_live_audio_room/ZIMConversationNotificationStatusSetResult-class.md)>



Available since: 2.1.5 and above.  




##### [setGroupAttributes](../zego_uikit_prebuilt_live_audio_room/ZIM/setGroupAttributes.md)(Map&lt;String, String> groupAttributes, String groupID) Future&lt;[ZIMGroupAttributesOperatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupAttributesOperatedResult-class.md)>



Available since: 2.1.5 and above.  




##### [setGroupMemberNickname](../zego_uikit_prebuilt_live_audio_room/ZIM/setGroupMemberNickname.md)(String nickname, String forUserID, String groupID) Future&lt;[ZIMGroupMemberNicknameUpdatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberNicknameUpdatedResult-class.md)>



Available since: 2.1.5 and above.  




##### [setGroupMemberRole](../zego_uikit_prebuilt_live_audio_room/ZIM/setGroupMemberRole.md)(int role, String forUserID, String groupID) Future&lt;[ZIMGroupMemberRoleUpdatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberRoleUpdatedResult-class.md)>



Available since: 2.1.5 and above.  




##### [setRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZIM/setRoomAttributes.md)(Map&lt;String, String> roomAttributes, String roomID, [ZIMRoomAttributesSetConfig](../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesSetConfig-class.md) config) Future&lt;[ZIMRoomAttributesOperatedCallResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomAttributesOperatedCallResult-class.md)>



Set room attributes (use this for all additions and changes).  




##### [setRoomMembersAttributes](../zego_uikit_prebuilt_live_audio_room/ZIM/setRoomMembersAttributes.md)(Map&lt;String, String> attributes, List&lt;String> userIDs, String roomID, [ZIMRoomMemberAttributesSetConfig](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberAttributesSetConfig-class.md) config) Future&lt;[ZIMRoomMembersAttributesOperatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMembersAttributesOperatedResult-class.md)>



Supported Versions: 2.4.0 and above.  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZIM/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [transferGroupOwner](../zego_uikit_prebuilt_live_audio_room/ZIM/transferGroupOwner.md)(String toUserID, String groupID) Future&lt;[ZIMGroupOwnerTransferredResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupOwnerTransferredResult-class.md)>



Available since: 2.1.5 and above.  




##### [updateGroupAvatarUrl](../zego_uikit_prebuilt_live_audio_room/ZIM/updateGroupAvatarUrl.md)(String groupAvatarUrl, String groupID) Future&lt;[ZIMGroupAvatarUrlUpdatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupAvatarUrlUpdatedResult-class.md)>



  




##### [updateGroupName](../zego_uikit_prebuilt_live_audio_room/ZIM/updateGroupName.md)(String groupName, String groupID) Future&lt;[ZIMGroupNameUpdatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupNameUpdatedResult-class.md)>



Available since: 2.1.5 and above.  




##### [updateGroupNotice](../zego_uikit_prebuilt_live_audio_room/ZIM/updateGroupNotice.md)(String groupNotice, String groupID) Future&lt;[ZIMGroupNoticeUpdatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMGroupNoticeUpdatedResult-class.md)>



Available since: 2.1.5 and above.  




##### [updateUserAvatarUrl](../zego_uikit_prebuilt_live_audio_room/ZIM/updateUserAvatarUrl.md)(String userAvatarUrl) Future&lt;[ZIMUserAvatarUrlUpdatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMUserAvatarUrlUpdatedResult-class.md)>



Available since: 2.3.0 and above.  




##### [updateUserExtendedData](../zego_uikit_prebuilt_live_audio_room/ZIM/updateUserExtendedData.md)(String extendedData) Future&lt;[ZIMUserExtendedDataUpdatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMUserExtendedDataUpdatedResult-class.md)>



Available since: 2.2.0 and above.  




##### [updateUserName](../zego_uikit_prebuilt_live_audio_room/ZIM/updateUserName.md)(String userName) Future&lt;[ZIMUserNameUpdatedResult](../zego_uikit_prebuilt_live_audio_room/ZIMUserNameUpdatedResult-class.md)>



Available since: 2.2.0 and above.  




##### [uploadLog](../zego_uikit_prebuilt_live_audio_room/ZIM/uploadLog.md)() Future&lt;void>



Upload log and call after setting up log path.  






## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZIM/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_







## Static Methods

##### [create](../zego_uikit_prebuilt_live_audio_room/ZIM/create.md)([ZIMAppConfig](../zego_uikit_prebuilt_live_audio_room/ZIMAppConfig-class.md) config) [ZIM](../zego_uikit_prebuilt_live_audio_room/ZIM-class.md)?



Create a ZIM instance.  




##### [getInstance](../zego_uikit_prebuilt_live_audio_room/ZIM/getInstance.md)() [ZIM](../zego_uikit_prebuilt_live_audio_room/ZIM-class.md)?



Get the SDK's instance  




##### [getVersion](../zego_uikit_prebuilt_live_audio_room/ZIM/getVersion.md)() Future&lt;String>



Gets the SDK's version number.  




##### [setCacheConfig](../zego_uikit_prebuilt_live_audio_room/ZIM/setCacheConfig.md)([ZIMCacheConfig](../zego_uikit_prebuilt_live_audio_room/ZIMCacheConfig-class.md) config) dynamic



Set cache related configuration.  




##### [setLogConfig](../zego_uikit_prebuilt_live_audio_room/ZIM/setLogConfig.md)([ZIMLogConfig](../zego_uikit_prebuilt_live_audio_room/ZIMLogConfig-class.md) config) dynamic



Set log related configuration.  












