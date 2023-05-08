

# ZegoMenuBarButtonName enum

<p>在顶部或者底部工具栏中可以添加的预定义按钮。</p>
<p>请注意这些按钮与角色无关，可以添加到任何人的工具栏上。Live Audio Room SDK只是默认根据角色预先定于有哪些按钮可以显示在对应角色的工具栏上。
比如你不想在 seat 上的 speaker 关闭自己的麦克风，那么你就不要把 toggleMicrophoneButton 添加到 ZegoBottomMenuBarConfig.speakerButtons 中即可。
比如你的业务场景希望观众也能查看成员列表，或者不希望观众查看成员列表等等。
比如你的业务场景只允许 host 邀请观众上到 seat 而不允许观众自行申请成为 speaker，那么你就不要把 applyToTakeSeatButton 添加到 ZegoBottomMenuBarConfig.audienceButtons 中即可。</p>

**Inheritance**

- Object
- Enum
- ZegoMenuBarButtonName

## Constructors

`ZegoMenuBarButtonName` ()

  _const_ 

## Values

##### `leaveButton` const `ZegoMenuBarButtonName`

<p>离开语聊房的按钮，你可以主动往底部或者顶部工具栏添加离开语聊房的按钮以根据你的业务优化交互体验</p>  

##### `toggleMicrophoneButton` const `ZegoMenuBarButtonName`

<p>控制麦克风开关的按钮，</p>  

##### `showMemberListButton` const `ZegoMenuBarButtonName`

<p>控制显示或者隐藏成员列表的按钮</p>  

##### `soundEffectButton` const `ZegoMenuBarButtonName`

<p>控制显示或者隐藏 sound effect 调节面板。通常只有 host 和 speaker 会讲话，所以通常只会把这个按钮显示在这两者的工具栏上。</p>  

##### `applyToTakeSeatButton` const `ZegoMenuBarButtonName`

<p>用于观众申请获得seat以跟其他人一起语音聊天的按钮。所以通常只放在观众工具栏上。</p>  

##### `minimizingButton` const `ZegoMenuBarButtonName`

<p>在App内最小化当前语聊房屏幕的按钮。点击后语聊房屏幕会缩小成一个可以在App内拖动小 Widget。</p>  

##### `closeSeatButton` const `ZegoMenuBarButtonName`

<p>控制打开或者关闭坐席的按钮。打开坐席后，所有观众都可以自由选择空的seat坐上去开始跟其他人聊天。如果关闭的话则观众要通过向 host 申请才能坐到 seat 上或者 host 主动邀请观众也行。</p>  


## Constants

##### `values` const List&lt;`ZegoMenuBarButtonName`>

A constant List of the values in this enum, in order of their declaration.  







