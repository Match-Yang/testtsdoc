


# ZegoLiveAudioRoomController class









<p>用于控制语聊房功能。如果默认的语聊房UI和交互不能满足你的需求，那么你可以通过这个Controller来主动坐业务逻辑控制。
这个类通过 ZegoUIKitPrebuiltLiveAudioRoom 构造方法的 controller 参数进行使用</p>




## Constructors

[ZegoLiveAudioRoomController](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/ZegoLiveAudioRoomController.md) ()

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [acceptHostTakeSeatInvitation](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/acceptHostTakeSeatInvitation.md)({required BuildContext context}) Future&lt;bool>



接受主持人占座邀请。其中<code>context</code> 为Flutter上下文对象  




##### [acceptSeatTakingRequest](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/acceptSeatTakingRequest.md)(String audienceUserID) Future&lt;bool>



主播接受id为<code>audienceUserID</code>的观众占座位请求  




##### [applyToTakeSeat](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/applyToTakeSeat.md)() Future&lt;bool>



观众主动请求占座位  




##### [cancelSeatTakingRequest](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/cancelSeatTakingRequest.md)() Future&lt;bool>



观众取消请求占座位  




##### [closeSeats](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/closeSeats.md)() Future&lt;bool>



关闭座位
关闭后观众要通过向 host 申请才能坐到 seat 上或者 host 主动邀请观众也行  




##### [inviteAudienceToTakeSeat](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/inviteAudienceToTakeSeat.md)(String userID) Future&lt;bool>



Host invite the audience with id <code>userID</code> to take seat  




##### [leaveSeat](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/leaveSeat.md)({bool showDialog = true}) Future&lt;bool>



speaker调用该方法可以离开座位
如果 <code>showDialog</code> 参数为 true，则在离开座位前会弹出一个二次确认的对话框。  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [openSeats](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/openSeats.md)() Future&lt;bool>



打开座位
打开座位后，所有观众都可以自由选择空的seat坐上去开始跟其他人聊天  




##### [rejectSeatTakingRequest](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/rejectSeatTakingRequest.md)(String audienceUserID) Future&lt;bool>



主播拒绝id为<code>audienceUserID</code>的观众占座位请求  




##### [removeSpeakerFromSeat](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/removeSpeakerFromSeat.md)(String userID) Future&lt;void>



将user id 为<code>userID</code>的speaker从座位上移除  




##### [takeSeat](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/takeSeat.md)(int index) Future&lt;bool>



让观众占据编号为<code>index</code>的座位
座位编号从0开始，从左往右从上往下递增。  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [turnMicrophoneOn](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/turnMicrophoneOn.md)(bool isOn, {String? userID}) void



打开/关闭指定用户的麦克风
如果 <code>userID</code> 为空或 null，则打开或关闭本地麦克风，否则打开或者关闭指定<code>userID</code>的麦克风。
参数 <code>isOn</code>：是否打开麦克风  






## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomController/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















