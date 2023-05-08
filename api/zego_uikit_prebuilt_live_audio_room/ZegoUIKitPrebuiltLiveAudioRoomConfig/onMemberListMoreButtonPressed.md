


# onMemberListMoreButtonPressed property







(void Function([ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) user)?) onMemberListMoreButtonPressed
  
_<span class="feature">read / write</span>_



<p>成员列表上与<code>user</code>对应行的"更多"按钮被按下时的回调方法。
如果你希望在点击成员列表上的更多按钮时能做更多操作，比如查看对应<code>user</code>的资料</p>
<p>注意，当你设置了这个回调后，原来点击成员列表更多按钮弹出菜单等默认行为都会失效，需要你自己处理。可以参考<code>ZegoLiveAudioRoomController</code>的使用。</p>



## Implementation

```dart
void Function(ZegoUIKitUser user)? onMemberListMoreButtonPressed;
```







