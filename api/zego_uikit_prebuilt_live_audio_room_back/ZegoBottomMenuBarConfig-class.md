

# ZegoBottomMenuBarConfig class

<p>底部菜单栏（工具栏）的配置项</p>

## Constructors

`ZegoBottomMenuBarConfig` ({bool showInRoomMessageButton = true, List&lt;`ZegoMenuBarButtonName`> hostButtons = const [ZegoMenuBarButtonName.soundEffectButton, ZegoMenuBarButtonName.toggleMicrophoneButton, ZegoMenuBarButtonName.showMemberListButton, ZegoMenuBarButtonName.closeSeatButton], List&lt;`ZegoMenuBarButtonName`> speakerButtons = const [ZegoMenuBarButtonName.soundEffectButton, ZegoMenuBarButtonName.toggleMicrophoneButton, ZegoMenuBarButtonName.showMemberListButton], List&lt;`ZegoMenuBarButtonName`> audienceButtons = const [ZegoMenuBarButtonName.showMemberListButton, ZegoMenuBarButtonName.applyToTakeSeatButton], List&lt;Widget> hostExtendButtons = const [], List&lt;Widget> speakerExtendButtons = const [], List&lt;Widget> audienceExtendButtons = const [], int maxCount = 5})

## Properties

##### `audienceButtons` &#8596; List&lt;`ZegoMenuBarButtonName`>

当用户角色为audience时会显示的预定义按钮列表  
_<span class="feature">read / write</span>_

##### `audienceExtendButtons` &#8596; List&lt;Widget>

当用户角色为audience时会显示的自定义按钮列表  
_<span class="feature">read / write</span>_


##### `hostButtons` &#8596; List&lt;`ZegoMenuBarButtonName`>

当用户角色为host时会显示的预定义按钮列表  
_<span class="feature">read / write</span>_

##### `hostExtendButtons` &#8596; List&lt;Widget>

当用户角色为host时会显示的自定义按钮列表  
_<span class="feature">read / write</span>_

##### `maxCount` &#8596; int

控制菜单栏（工具栏）最多显示的按钮数量（包含预定义和自定义按钮）。
当超过<a href="../zego_uikit_prebuilt_live_audio_room/ZegoBottomMenuBarConfig/maxCount.md">maxCount</a>限制后，就会出现"更多"按钮，点击后会弹出一个面板显示其他无法在菜单栏（工具栏）显示的按钮。  
_<span class="feature">read / write</span>_


##### `showInRoomMessageButton` &#8596; bool

当设置为<code>true</code>时，会显示发送消息的按钮。如果你想禁止大家在语聊房内发送文字消息，那么将其设置成<code>false</code>即可。  
_<span class="feature">read / write</span>_

##### `speakerButtons` &#8596; List&lt;`ZegoMenuBarButtonName`>

当用户角色为speaker时会显示的预定义按钮列表  
_<span class="feature">read / write</span>_

##### `speakerExtendButtons` &#8596; List&lt;Widget>

当用户角色为speaker时会显示的自定义按钮列表  
_<span class="feature">read / write</span>_
