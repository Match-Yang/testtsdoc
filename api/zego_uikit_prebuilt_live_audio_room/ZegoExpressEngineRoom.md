


# ZegoExpressEngineRoom extension
on [ZegoExpressEngine](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine-class.md)
















## Methods

##### [loginRoom](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/loginRoom.md)(String roomID, [ZegoUser](../zego_uikit_prebuilt_live_audio_room/ZegoUser-class.md) user, {[ZegoRoomConfig](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig-class.md)? config}) Future&lt;[ZegoRoomLoginResult](../zego_uikit_prebuilt_live_audio_room/ZegoRoomLoginResult-class.md)>



Log in to the room by configuring advanced properties, and return the login result through the callback parameter. You must log in to the room before pushing or pulling the stream.  




##### [logoutRoom](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/logoutRoom.md)([String? roomID]) Future&lt;[ZegoRoomLogoutResult](../zego_uikit_prebuilt_live_audio_room/ZegoRoomLogoutResult-class.md)>



Logs out of a room.  




##### [renewToken](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/renewToken.md)(String roomID, String token) Future&lt;void>



Renew token.  




##### [setRoomExtraInfo](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/setRoomExtraInfo.md)(String roomID, String key, String value) Future&lt;[ZegoRoomSetRoomExtraInfoResult](../zego_uikit_prebuilt_live_audio_room/ZegoRoomSetRoomExtraInfoResult-class.md)>



Set room extra information.  




##### [switchRoom](../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineRoom/switchRoom.md)(String fromRoomID, String toRoomID, {[ZegoRoomConfig](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig-class.md)? config}) Future&lt;void>



Switch the room with advanced room configurations.  


















