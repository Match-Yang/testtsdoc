


# turnMicrophoneOn method








void turnMicrophoneOn
(bool isOn, {String? userID})





<p>打开/关闭指定用户的麦克风
如果 <code>userID</code> 为空或 null，则打开或关闭本地麦克风，否则打开或者关闭指定<code>userID</code>的麦克风。
参数 <code>isOn</code>：是否打开麦克风</p>



## Implementation

```dart
void turnMicrophoneOn(bool isOn, {String? userID}) {
  ZegoUIKit().turnMicrophoneOn(isOn, userID: userID);
}
```







