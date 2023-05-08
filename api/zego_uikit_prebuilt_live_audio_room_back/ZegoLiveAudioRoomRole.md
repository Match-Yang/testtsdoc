

# ZegoLiveAudioRoomRole enum

<p>用户在语聊房中的角色</p>

**Inheritance**

- Object
- Enum
- ZegoLiveAudioRoomRole

## Constructors

`ZegoLiveAudioRoomRole` ()

  _const_ 

## Values

##### `host` const `ZegoLiveAudioRoomRole`

<p>host 是语聊房中权限最高的用户，可以控制语聊房内所有功能。比如禁止观众文字聊天、邀请观众到seat上成为speaker、将speaker踢下坐席成为观众等等。</p>  

##### `speaker` const `ZegoLiveAudioRoomRole`

<p>speaker 可以在语聊房内跟host或者其他speaker通过语音聊天。除此之外没有其他特殊权限。</p>  

##### `audience` const `ZegoLiveAudioRoomRole`

<p>audience 可以在语聊房内听host和其他speaker语音聊天，也可以发文字聊天。</p>  

## Constants

##### `values` const List&lt;`ZegoLiveAudioRoomRole`>

A constant List of the values in this enum, in order of their declaration.  

