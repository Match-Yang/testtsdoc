


# onMicrophoneTurnOnByOthersConfirmation property







(Future&lt;bool> Function(BuildContext context)?) onMicrophoneTurnOnByOthersConfirmation
  
_<span class="feature">read / write</span>_



<p>这个回调方法在别人请求打开你的麦克风时会被调用，通常是host要打开speaker的麦克风
这个方法要求返回一个异步结果。你可以在这个回调中弹出一个对话框以确认是否要打开麦克风。
你也可以不做任何处理直接返回<code>true</code>，这表示别人发起请求要打开你的麦克风时能直接打开。
这个方法默认不做任何处理直接返回<code>false</code>，表示别人无法开启你的麦克风。</p>



## Implementation

```dart
Future<bool> Function(BuildContext context)?
    onMicrophoneTurnOnByOthersConfirmation;
```







