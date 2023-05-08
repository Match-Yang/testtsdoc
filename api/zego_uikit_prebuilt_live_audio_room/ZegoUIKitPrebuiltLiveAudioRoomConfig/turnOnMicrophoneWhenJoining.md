


# turnOnMicrophoneWhenJoining property







bool turnOnMicrophoneWhenJoining
  
_<span class="feature">read / write</span>_



<p>加入语聊房时是否打开麦克风
如果你想加入语聊房时关闭自己的麦克风，那么将这个值设置为 false ；如果你想加入语聊房时打开自己的麦克风，那么将这个值设置为 true 。默认值是<code>true</code>
注意，这个参数与角色无关。即使是观众，也可以将这个值设置为true，那么他/她加入房间后就可以开始通过语音跟其他人聊天。所以一般情况下，如果role是观众，那么这里应该填成false</p>



## Implementation

```dart
bool turnOnMicrophoneWhenJoining;
```







