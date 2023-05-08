


# onLeaveConfirmation property







(Future&lt;bool> Function(BuildContext context)?) onLeaveConfirmation
  
_<span class="feature">read / write</span>_



<p>离开语聊房前的二次确认回调方法。</p>
<p>如果你希望在退出语聊房前不仅仅弹一个简单的对话框，而是需要做更多复杂的业务逻辑，比如向后台更新一些记录，那么你可以通过<code>onLeaveConfirmation</code>参数来设置。
这个参数要求你提供一个回调方法，该方法需要返回一个异步结果。
if you return true in the callback, prebuilt page will quit and return to your previous page, otherwise will ignore.</p>



## Implementation

```dart
Future<bool> Function(BuildContext context)? onLeaveConfirmation;
```







