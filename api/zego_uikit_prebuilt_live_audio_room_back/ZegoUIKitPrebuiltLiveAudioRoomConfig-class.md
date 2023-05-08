

# ZegoUIKitPrebuiltLiveAudioRoomConfig class

<p>初始化语聊房的配置</p>

## Constructors

`ZegoUIKitPrebuiltLiveAudioRoomConfig` ({bool turnOnMicrophoneWhenJoining = true, bool useSpeakerWhenJoining = true, bool closeSeatsWhenJoining = true, `ZegoLiveAudioRoomSeatConfig`? seatConfig, `ZegoTopMenuBarConfig`? topMenuBarConfig, `ZegoBottomMenuBarConfig`? bottomMenuBarConfig, `ZegoLiveAudioRoomLayoutConfig`? layoutConfig, `ZegoInRoomMessageViewConfig`? messageConfig, `ZegoAudioEffectConfig`? effectConfig, List&lt;int> hostSeatIndexes = const `0], `ZegoDialogInfo`? confirmDialogInfo, Future&lt;bool> onLeaveConfirmation(BuildContext context)?, VoidCallback? onLeaveLiveAudioRoom, Widget? background, String? userAvatarUrl, Map&lt;String, String> userInRoomAttributes = const {}, void onUserCountOrPropertyChanged(List&lt;ZegoUIKitUser> users)?, VoidCallback? onSeatClosed, VoidCallback? onSeatsOpened, void onSeatClicked(int index, ZegoUIKitUser? user)?, void onSeatsChanged(Map&lt;int, ZegoUIKitUser> takenSeats, List&lt;int> untakenSeats)?, void onSeatTakingRequested(ZegoUIKitUser audience)?, void onSeatTakingRequestCanceled(ZegoUIKitUser audience)?, VoidCallback? onInviteAudienceToTakeSeatFailed, VoidCallback? onSeatTakingInviteRejected, VoidCallback? onSeatTakingRequestFailed, VoidCallback? onSeatTakingRequestRejected, VoidCallback? onHostSeatTakingInviteSent, void onMemberListMoreButtonPressed(ZegoUIKitUser user)?, [ZegoInnerText`? translationText})

`ZegoUIKitPrebuiltLiveAudioRoomConfig.audience` ()

audience 默认的初始化参数。如果某个配置项不符合你的预期，你可以直接覆盖这个配置项的值。   

`ZegoUIKitPrebuiltLiveAudioRoomConfig.host` ()

Host 默认的初始化参数。如果某个配置项不符合你的预期，你可以直接覆盖这个配置项的值。   

## Properties

##### `audioEffectConfig` &#8596; `ZegoAudioEffectConfig`

你可以用来修改你的声音以及控制Reverb  
_<span class="feature">read / write</span>_

##### `background` &#8596; Widget?

语聊房屏幕的背景  
_<span class="feature">read / write</span>_

##### `bottomMenuBarConfig` &#8596; `ZegoBottomMenuBarConfig`

底部菜单栏（工具栏）的配置项  
_<span class="feature">read / write</span>_

##### `closeSeatsWhenJoining` &#8596; bool

Specifies whether to lock the seat automatically after entering the room
默认值是<code>true</code>
只有host设置生效  
_<span class="feature">read / write</span>_

##### `confirmDialogInfo` &#8596; `ZegoDialogInfo`?

退出语聊房时的二期确认弹框信息
如果不设置，那么点击退出按钮时会直接退出语聊房。
而如果设置了，就会在点击退出按钮时弹出确认弹框，在你选择确认退出后才会退出。  
_<span class="feature">read / write</span>_


##### `hostSeatIndexes` &#8596; List&lt;int>

指定被host占据的座位列表。指定后，这些座位只能给host使用，speaker和audience都不能占用。
默认值是<code>[0]</code>  
_<span class="feature">read / write</span>_

##### `innerText` &#8596; `ZegoInnerText`

UI上所有文案的修改控制项。
UI上可见的所有文案都可以通过这一个属性进行修改。  
_<span class="feature">read / write</span>_

##### `inRoomMessageViewConfig` &#8596; `ZegoInRoomMessageViewConfig`

消息列表的配置项  
_<span class="feature">read / write</span>_

##### `layoutConfig` &#8596; `ZegoLiveAudioRoomLayoutConfig`

语聊房默认支持多行和多列座位自由布局。你可以使用这个参数控制具体每行每列的样式。  
_<span class="feature">read / write</span>_

##### `onHostSeatTakingInviteSent` &#8596; VoidCallback?

观众收到了主播邀请自己上座的通知  
_<span class="feature">read / write</span>_

##### `onInviteAudienceToTakeSeatFailed` &#8596; VoidCallback?

主播收到了邀请观众上座失败的通知。通常是因为网络问题导致的，或者观众已经退出App登录了你无法再发送邀请。  
_<span class="feature">read / write</span>_

##### `onLeaveConfirmation` &#8596; (Future&lt;bool> Function(BuildContext context)?)

离开语聊房前的二次确认回调方法。  
_<span class="feature">read / write</span>_

##### `onLeaveLiveAudioRoom` &#8596; VoidCallback?

在离开语聊房后会触发该回调。你可以在这个回调里做一些业务相关的提示等等。  
_<span class="feature">read / write</span>_

##### `onMemberListMoreButtonPressed` &#8596; (void Function(ZegoUIKitUser user)?)

成员列表上与<code>user</code>对应行的"更多"按钮被按下时的回调方法。
如果你希望在点击成员列表上的更多按钮时能做更多操作，比如查看对应<code>user</code>的资料  
_<span class="feature">read / write</span>_

##### `onMicrophoneTurnOnByOthersConfirmation` &#8596; (Future&lt;bool> Function(BuildContext context)?)

这个回调方法在别人请求打开你的麦克风时会被调用，通常是host要打开speaker的麦克风
这个方法要求返回一个异步结果。你可以在这个回调中弹出一个对话框以确认是否要打开麦克风。
你也可以不做任何处理直接返回<code>true</code>，这表示别人发起请求要打开你的麦克风时能直接打开。
这个方法默认不做任何处理直接返回<code>false</code>，表示别人无法开启你的麦克风。  
_<span class="feature">read / write</span>_

##### `onSeatClicked` &#8596; (void Function(int index, ZegoUIKitUser? user)?)

A callback function that is called when a seat is clicked.  
_<span class="feature">read / write</span>_

##### `onSeatClosed` &#8596; VoidCallback?

座位已经被关闭的通知。关闭后观众要通过向 host 申请才能坐到 seat 上或者 host 主动邀请观众也行。  
_<span class="feature">read / write</span>_

##### `onSeatsChanged` &#8596; (void Function(Map&lt;int, ZegoUIKitUser> takenSeats, List&lt;int> untakenSeats)?)

A callback function that is called when someone gets on/off/switches seat  
_<span class="feature">read / write</span>_

##### `onSeatsOpened` &#8596; VoidCallback?

座位已经被打开的通知。打开坐席后，所有观众都可以自由选择空的seat坐上去开始跟其他人聊天。  
_<span class="feature">read / write</span>_

##### `onSeatTakingInviteRejected` &#8596; VoidCallback?

主播收到了邀请观众上座被拒绝的通知  
_<span class="feature">read / write</span>_

##### `onSeatTakingRequestCanceled` &#8596; (void Function(ZegoUIKitUser audience)?)

主播收到了<a href="../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/ZegoUIKitPrebuiltLiveAudioRoomConfig.audience.md">audience</a>取消申请座位请求的通知  
_<span class="feature">read / write</span>_

##### `onSeatTakingRequested` &#8596; (void Function(ZegoUIKitUser audience)?)

主播收到了<a href="../zego_uikit_prebuilt_live_audio_room/ZegoUIKitPrebuiltLiveAudioRoomConfig/ZegoUIKitPrebuiltLiveAudioRoomConfig.audience.md">audience</a>申请座位的请求  
_<span class="feature">read / write</span>_

##### `onSeatTakingRequestFailed` &#8596; VoidCallback?

观众收到了申请上座失败的通知。通常是因为网络问题导致的，或者主播已经退出App登录了你无法再发送申请。  
_<span class="feature">read / write</span>_

##### `onSeatTakingRequestRejected` &#8596; VoidCallback?

The audience received a notification that their request to take seats was declined by the host.  
_<span class="feature">read / write</span>_

##### `onUserCountOrPropertyChanged` &#8596; (void Function(List&lt;ZegoUIKitUser> users)?)

当用户数量或者这些用户相关的attribute变更时会触发这个回调方法。  
_<span class="feature">read / write</span>_

##### `role` &#8596; `ZegoLiveAudioRoomRole`

指定加入语聊房时的初始角色。在加入后的角色变更不受该属性约束。  
_<span class="feature">read / write</span>_


##### `seatConfig` &#8596; `ZegoLiveAudioRoomSeatConfig`

针对每个座位的配置  
_<span class="feature">read / write</span>_

##### `takeSeatIndexWhenJoining` &#8596; int

指定加入语聊房时要占用的座位。只有role为 host 或者 speaker时有效。  
_<span class="feature">read / write</span>_

##### `topMenuBarConfig` &#8596; `ZegoTopMenuBarConfig`

顶部菜单栏（工具栏）的配置项  
_<span class="feature">read / write</span>_

##### `turnOnMicrophoneWhenJoining` &#8596; bool

加入语聊房时是否打开麦克风
默认值是<code>true</code>
注意，这个参数与角色无关。即使是观众，也可以将这个值设置为true，那么他/她加入房间后就可以开始通过语音跟其他人聊天。所以一般情况下，如果role是观众，那么这里应该填成false  
_<span class="feature">read / write</span>_

##### `userAvatarUrl` &#8596; String?

设置当前用户的头像URL
注意，头像长度默认最大支持64字节，超过这个限制会导致头像无法显示。我们建议你使用短链接来设置头像URL。
如果你确实有使用长头像URL的需求，请联系技术支持。  
_<span class="feature">read / write</span>_

##### `userInRoomAttributes` &#8596; Map&lt;String, String>

设置当前用户在当前加入的语聊房的属性
<code>userAvatarUrl</code>实际使用的也是这个属性，占用了key为avatar的一个属性  
_<span class="feature">read / write</span>_

##### `useSpeakerWhenJoining` &#8596; bool

加入语聊房时是否使用扬声器播放声音
默认值是<code>true</code>
如果这个值设置为<code>false</code>，那么就会使用系统默认的播放设备进行播放，比如听筒或者蓝牙耳机。  
_<span class="feature">read / write</span>_
