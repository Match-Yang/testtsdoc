


# onSeatClicked property







(void Function(int index, [ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)? user)?) onSeatClicked
  
_<span class="feature">read / write</span>_



<p>A callback function that is called when a seat is clicked.</p>
<p>The <code>index</code> parameter is the index of the seat that was clicked.</p>
<p>The <code>user</code> parameter is the user who is currently sitting in the seat,
or <code>null</code> if the seat is empty.
注意，当你设置了这个回调后，原来点击seat弹出菜单等默认行为都会失效，需要你自己处理。可以参考<code>ZegoLiveAudioRoomController</code>的使用。</p>



## Implementation

```dart
void Function(int index, ZegoUIKitUser? user)? onSeatClicked;
```







