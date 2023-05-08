

# ZegoLiveAudioRoomSeatConfig class

<p>控制座位行为和样式的配置项</p>

## Constructors

`ZegoLiveAudioRoomSeatConfig` ({Image? openIcon, Image? closeIcon, bool showSoundWaveInAudioMode = true, ZegoAvatarBuilder? avatarBuilder, ZegoAudioVideoViewForegroundBuilder? foregroundBuilder, ZegoAudioVideoViewBackgroundBuilder? backgroundBuilder})

## Properties

##### `avatarBuilder` &#8596; ZegoAvatarBuilder?

Use this to customize the avatar, and replace the default avatar with it.  
_<span class="feature">read / write</span>_

##### `backgroundBuilder` &#8596; ZegoAudioVideoViewBackgroundBuilder?

Use this to customize the background view of the seat, and the <code>ZegoUIKitPrebuiltLiveAudioRoom</code> returns the current user on the seat and the corresponding seat index.  
_<span class="feature">read / write</span>_

##### `closeIcon` &#8596; Image?

当所有座位被关闭后空座位显示的图标  
_<span class="feature">read / write</span>_

##### `foregroundBuilder` &#8596; ZegoAudioVideoViewForegroundBuilder?

Use this to customize the foreground view of the seat, and the <code>ZegoUIKitPrebuiltLiveAudioRoom</code> will returns the current user on the seat and the corresponding seat index.  
_<span class="feature">read / write</span>_


##### `openIcon` &#8596; Image?

当所有座位被打开后空座位显示的图标  
_<span class="feature">read / write</span>_


##### `showSoundWaveInAudioMode` &#8596; bool

_<span class="feature">read / write</span>_
