


# ZegoUIKitPrebuiltLiveAudioRoomConfig class









<p>初始化语聊房的配置
这个类用于 ZegoUIKitPrebuiltLiveAudioRoom 构造方法的 config 参数</p>




## Constructors

[ZegoUIKitPrebuiltLiveAudioRoomConfig](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/ZegoUIKitPrebuiltLiveAudioRoomConfig.md) ({bool turnOnMicrophoneWhenJoining = true, bool useSpeakerWhenJoining = true, bool closeSeatsWhenJoining = true, [ZegoLiveAudioRoomSeatConfig](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomSeatConfig-class.md)? seatConfig, [ZegoTopMenuBarConfig](../zego_uikit_prebuilt_live_audio_room/ZegoTopMenuBarConfig-class.md)? topMenuBarConfig, [ZegoBottomMenuBarConfig](../zego_uikit_prebuilt_live_audio_room/ZegoBottomMenuBarConfig-class.md)? bottomMenuBarConfig, [ZegoLiveAudioRoomLayoutConfig](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomLayoutConfig-class.md)? layoutConfig, [ZegoInRoomMessageViewConfig](../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessageViewConfig-class.md)? messageConfig, [ZegoAudioEffectConfig](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectConfig-class.md)? effectConfig, List&lt;int> hostSeatIndexes = const [0], [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)? confirmDialogInfo, Future&lt;bool> onLeaveConfirmation(BuildContext context)?, VoidCallback? onLeaveLiveAudioRoom, Widget? background, String? userAvatarUrl, Map&lt;String, String> userInRoomAttributes = const {}, void onUserCountOrPropertyChanged(List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)> users)?, VoidCallback? onSeatClosed, VoidCallback? onSeatsOpened, void onSeatClicked(int index, [ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)? user)?, void onSeatsChanged(Map&lt;int, [ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)> takenSeats, List&lt;int> untakenSeats)?, void onSeatTakingRequested([ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) audience)?, void onSeatTakingRequestCanceled([ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) audience)?, VoidCallback? onInviteAudienceToTakeSeatFailed, VoidCallback? onSeatTakingInviteRejected, VoidCallback? onSeatTakingRequestFailed, VoidCallback? onSeatTakingRequestRejected, VoidCallback? onHostSeatTakingInviteSent, void onMemberListMoreButtonPressed([ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) user)?, [ZegoInnerText](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText-class.md)? translationText})

   

[ZegoUIKitPrebuiltLiveAudioRoomConfig.audience](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/ZegoUIKitPrebuiltLiveAudioRoomConfig.audience.md) ()

audience 默认的初始化参数。如果某个配置项不符合你的预期，你可以直接覆盖这个配置项的值。   

[ZegoUIKitPrebuiltLiveAudioRoomConfig.host](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/ZegoUIKitPrebuiltLiveAudioRoomConfig.host.md) ()

Host 默认的初始化参数。如果某个配置项不符合你的预期，你可以直接覆盖这个配置项的值。   


## Properties

##### [audioEffectConfig](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/audioEffectConfig.md) &#8596; [ZegoAudioEffectConfig](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectConfig-class.md)



你可以用来修改你的声音以及控制Reverb  
_<span class="feature">read / write</span>_



##### [background](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/background.md) &#8596; Widget?



语聊房屏幕的背景  
_<span class="feature">read / write</span>_



##### [bottomMenuBarConfig](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/bottomMenuBarConfig.md) &#8596; [ZegoBottomMenuBarConfig](../zego_uikit_prebuilt_live_audio_room/ZegoBottomMenuBarConfig-class.md)



底部菜单栏（工具栏）的配置项  
_<span class="feature">read / write</span>_



##### [closeSeatsWhenJoining](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/closeSeatsWhenJoining.md) &#8596; bool



Specifies whether to lock the seat automatically after entering the room
默认值是<code>true</code>
只有host设置生效  
_<span class="feature">read / write</span>_



##### [confirmDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/confirmDialogInfo.md) &#8596; [ZegoDialogInfo](../zego_uikit_prebuilt_live_audio_room/ZegoDialogInfo-class.md)?



退出语聊房时的二期确认弹框信息
如果不设置，那么点击退出按钮时会直接退出语聊房。
而如果设置了，就会在点击退出按钮时弹出确认弹框，在你选择确认退出后才会退出。  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [hostSeatIndexes](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/hostSeatIndexes.md) &#8596; List&lt;int>



指定被host占据的座位列表。指定后，这些座位只能给host使用，speaker和audience都不能占用。
默认值是<code>[0]</code>  
_<span class="feature">read / write</span>_



##### [innerText](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/innerText.md) &#8596; [ZegoInnerText](../zego_uikit_prebuilt_live_audio_room/ZegoInnerText-class.md)



UI上所有文案的修改控制项。
UI上可见的所有文案都可以通过这一个属性进行修改。  
_<span class="feature">read / write</span>_



##### [inRoomMessageViewConfig](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/inRoomMessageViewConfig.md) &#8596; [ZegoInRoomMessageViewConfig](../zego_uikit_prebuilt_live_audio_room/ZegoInRoomMessageViewConfig-class.md)



消息列表的配置项  
_<span class="feature">read / write</span>_



##### [layoutConfig](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/layoutConfig.md) &#8596; [ZegoLiveAudioRoomLayoutConfig](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomLayoutConfig-class.md)



语聊房默认支持多行和多列座位自由布局。你可以使用这个参数控制具体每行每列的样式。  
_<span class="feature">read / write</span>_



##### [onHostSeatTakingInviteSent](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onHostSeatTakingInviteSent.md) &#8596; VoidCallback?



观众收到了主播邀请自己上座的通知  
_<span class="feature">read / write</span>_



##### [onInviteAudienceToTakeSeatFailed](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onInviteAudienceToTakeSeatFailed.md) &#8596; VoidCallback?



主播收到了邀请观众上座失败的通知。通常是因为网络问题导致的，或者观众已经退出App登录了你无法再发送邀请。  
_<span class="feature">read / write</span>_



##### [onLeaveConfirmation](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onLeaveConfirmation.md) &#8596; (Future&lt;bool> Function(BuildContext context)?)



离开语聊房前的二次确认回调方法。  
_<span class="feature">read / write</span>_



##### [onLeaveLiveAudioRoom](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onLeaveLiveAudioRoom.md) &#8596; VoidCallback?



在离开语聊房后会触发该回调。你可以在这个回调里做一些业务相关的提示等等。  
_<span class="feature">read / write</span>_



##### [onMemberListMoreButtonPressed](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onMemberListMoreButtonPressed.md) &#8596; (void Function([ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) user)?)



成员列表上与<code>user</code>对应行的"更多"按钮被按下时的回调方法。
如果你希望在点击成员列表上的更多按钮时能做更多操作，比如查看对应<code>user</code>的资料  
_<span class="feature">read / write</span>_



##### [onMicrophoneTurnOnByOthersConfirmation](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onMicrophoneTurnOnByOthersConfirmation.md) &#8596; (Future&lt;bool> Function(BuildContext context)?)



这个回调方法在别人请求打开你的麦克风时会被调用，通常是host要打开speaker的麦克风
这个方法要求返回一个异步结果。你可以在这个回调中弹出一个对话框以确认是否要打开麦克风。
你也可以不做任何处理直接返回<code>true</code>，这表示别人发起请求要打开你的麦克风时能直接打开。
这个方法默认不做任何处理直接返回<code>false</code>，表示别人无法开启你的麦克风。  
_<span class="feature">read / write</span>_



##### [onSeatClicked](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onSeatClicked.md) &#8596; (void Function(int index, [ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)? user)?)



A callback function that is called when a seat is clicked.  
_<span class="feature">read / write</span>_



##### [onSeatClosed](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onSeatClosed.md) &#8596; VoidCallback?



座位已经被关闭的通知。关闭后观众要通过向 host 申请才能坐到 seat 上或者 host 主动邀请观众也行。  
_<span class="feature">read / write</span>_



##### [onSeatsChanged](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onSeatsChanged.md) &#8596; (void Function(Map&lt;int, [ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)> takenSeats, List&lt;int> untakenSeats)?)



A callback function that is called when someone gets on/off/switches seat  
_<span class="feature">read / write</span>_



##### [onSeatsOpened](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onSeatsOpened.md) &#8596; VoidCallback?



座位已经被打开的通知。打开坐席后，所有观众都可以自由选择空的seat坐上去开始跟其他人聊天。  
_<span class="feature">read / write</span>_



##### [onSeatTakingInviteRejected](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onSeatTakingInviteRejected.md) &#8596; VoidCallback?



主播收到了邀请观众上座被拒绝的通知  
_<span class="feature">read / write</span>_



##### [onSeatTakingRequestCanceled](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onSeatTakingRequestCanceled.md) &#8596; (void Function([ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) audience)?)



主播收到了<a href="../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/ZegoUIKitPrebuiltLiveAudioRoomConfig.audience.md">audience</a>取消申请座位请求的通知  
_<span class="feature">read / write</span>_



##### [onSeatTakingRequested](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onSeatTakingRequested.md) &#8596; (void Function([ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) audience)?)



主播收到了<a href="../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/ZegoUIKitPrebuiltLiveAudioRoomConfig.audience.md">audience</a>申请座位的请求  
_<span class="feature">read / write</span>_



##### [onSeatTakingRequestFailed](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onSeatTakingRequestFailed.md) &#8596; VoidCallback?



观众收到了申请上座失败的通知。通常是因为网络问题导致的，或者主播已经退出App登录了你无法再发送申请。  
_<span class="feature">read / write</span>_



##### [onSeatTakingRequestRejected](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onSeatTakingRequestRejected.md) &#8596; VoidCallback?



The audience received a notification that their request to take seats was declined by the host.  
_<span class="feature">read / write</span>_



##### [onUserCountOrPropertyChanged](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/onUserCountOrPropertyChanged.md) &#8596; (void Function(List&lt;[ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)> users)?)



当用户数量或者这些用户相关的attribute变更时会触发这个回调方法。  
_<span class="feature">read / write</span>_



##### [role](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/role.md) &#8596; [ZegoLiveAudioRoomRole](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomRole.md)



指定加入语聊房时的初始角色。在加入后的角色变更不受该属性约束。  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [seatConfig](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/seatConfig.md) &#8596; [ZegoLiveAudioRoomSeatConfig](../zego_uikit_prebuilt_live_audio_room/ZegoLiveAudioRoomSeatConfig-class.md)



针对每个座位的配置  
_<span class="feature">read / write</span>_



##### [takeSeatIndexWhenJoining](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/takeSeatIndexWhenJoining.md) &#8596; int



指定加入语聊房时要占用的座位。只有role为 host 或者 speaker时有效。  
_<span class="feature">read / write</span>_



##### [topMenuBarConfig](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/topMenuBarConfig.md) &#8596; [ZegoTopMenuBarConfig](../zego_uikit_prebuilt_live_audio_room/ZegoTopMenuBarConfig-class.md)



顶部菜单栏（工具栏）的配置项  
_<span class="feature">read / write</span>_



##### [turnOnMicrophoneWhenJoining](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/turnOnMicrophoneWhenJoining.md) &#8596; bool



加入语聊房时是否打开麦克风
如果你想加入语聊房时关闭自己的麦克风，那么将这个值设置为 false ；如果你想加入语聊房时打开自己的麦克风，那么将这个值设置为 true 。默认值是<code>true</code>
注意，这个参数与角色无关。即使是观众，也可以将这个值设置为true，那么他/她加入房间后就可以开始通过语音跟其他人聊天。所以一般情况下，如果role是观众，那么这里应该填成false  
_<span class="feature">read / write</span>_



##### [userAvatarUrl](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/userAvatarUrl.md) &#8596; String?



设置当前用户的头像URL
注意，头像长度默认最大支持64字节，超过这个限制会导致头像无法显示。我们建议你使用短链接来设置头像URL。
如果你确实有使用长头像URL的需求，请联系技术支持。  
_<span class="feature">read / write</span>_



##### [userInRoomAttributes](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/userInRoomAttributes.md) &#8596; Map&lt;String, String>



设置当前用户在当前加入的语聊房的属性
<code>userAvatarUrl</code>实际使用的也是这个属性，占用了key为avatar的一个属性  
_<span class="feature">read / write</span>_



##### [useSpeakerWhenJoining](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/useSpeakerWhenJoining.md) &#8596; bool



加入语聊房时是否使用扬声器播放声音
默认值是<code>true</code>
如果这个值设置为<code>false</code>，那么就会使用系统默认的播放设备进行播放，比如听筒或者蓝牙耳机。  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















