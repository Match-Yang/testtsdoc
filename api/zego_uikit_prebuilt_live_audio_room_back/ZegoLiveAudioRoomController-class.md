

# ZegoLiveAudioRoomController class

<p>用于控制语聊房功能。如果默认的语聊房UI和交互不能满足你的需求，那么你可以通过这个Controller来主动坐业务逻辑控制。</p>

## Constructors

`ZegoLiveAudioRoomController` ()

## Properties



## Methods

##### `acceptHostTakeSeatInvitation`({required BuildContext context}) Future&lt;bool>

接受主持人占座邀请。其中<code>context</code> 为Flutter上下文对象  

##### `acceptSeatTakingRequest`(String audienceUserID) Future&lt;bool>

主播接受id为<code>audienceUserID</code>的观众占座位请求  

##### `applyToTakeSeat`() Future&lt;bool>

观众主动请求占座位  

##### `cancelSeatTakingRequest`() Future&lt;bool>

观众取消请求占座位  

##### `closeSeats`() Future&lt;bool>

关闭座位
关闭后观众要通过向 host 申请才能坐到 seat 上或者 host 主动邀请观众也行  

##### `inviteAudienceToTakeSeat`(String userID) Future&lt;bool>

Host invite the audience with id <code>userID</code> to take seat  

##### `leaveSeat`({bool showDialog = true}) Future&lt;bool>

speaker调用该方法可以离开座位
如果 <code>showDialog</code> 参数为 true，则在离开座位前会弹出一个二次确认的对话框。  


##### `openSeats`() Future&lt;bool>

打开座位
打开座位后，所有观众都可以自由选择空的seat坐上去开始跟其他人聊天  

##### `rejectSeatTakingRequest`(String audienceUserID) Future&lt;bool>

主播拒绝id为<code>audienceUserID</code>的观众占座位请求  

##### `removeSpeakerFromSeat`(String userID) Future&lt;void>

将user id 为<code>userID</code>的speaker从座位上移除  

##### `takeSeat`(int index) Future&lt;bool>

让观众占据编号为<code>index</code>的座位
座位编号从0开始，从左往右从上往下递增。  


##### `turnMicrophoneOn`(bool isOn, {String? userID}) void

打开/关闭指定用户的麦克风
如果 <code>userID</code> 为空或 null，则打开或关闭本地麦克风，否则打开或者关闭指定<code>userID</code>的麦克风。
参数 <code>isOn</code>：是否打开麦克风  
