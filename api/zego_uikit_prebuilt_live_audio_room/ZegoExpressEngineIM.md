


# ZegoExpressEngineIM extension
on [ZegoExpressEngine](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine-class.md)
















## Methods

##### [createRealTimeSequentialDataManager](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/createRealTimeSequentialDataManager.md)(String roomID) Future&lt;[ZegoRealTimeSequentialDataManager](../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md)?>



Create the real time sequential data manager instance  




##### [destroyRealTimeSequentialDataManager](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/destroyRealTimeSequentialDataManager.md)([ZegoRealTimeSequentialDataManager](../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md) manager) Future&lt;void>



Destroy the real time sequential data manager instance  




##### [sendBarrageMessage](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/sendBarrageMessage.md)(String roomID, String message) Future&lt;[ZegoIMSendBarrageMessageResult](../zego_uikit_prebuilt_live_audio_room/ZegoIMSendBarrageMessageResult-class.md)>



Sends a Barrage Message (bullet screen) to all users in the same room, without guaranteeing the delivery.  




##### [sendBroadcastMessage](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/sendBroadcastMessage.md)(String roomID, String message) Future&lt;[ZegoIMSendBroadcastMessageResult](../zego_uikit_prebuilt_live_audio_room/ZegoIMSendBroadcastMessageResult-class.md)>



Sends a Broadcast Message.  




##### [sendCustomCommand](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/sendCustomCommand.md)(String roomID, String command, List&lt;[ZegoUser](../zego_uikit_prebuilt_live_audio_room/ZegoUser-class.md)> toUserList) Future&lt;[ZegoIMSendCustomCommandResult](../zego_uikit_prebuilt_live_audio_room/ZegoIMSendCustomCommandResult-class.md)>



Sends a Custom Command to the specified users in the same room.  


















