


# leaveSeat method








Future&lt;bool> leaveSeat
({bool showDialog = true})





<p>speaker调用该方法可以离开座位
如果 <code>showDialog</code> 参数为 true，则在离开座位前会弹出一个二次确认的对话框。</p>



## Implementation

```dart
Future<bool> leaveSeat({bool showDialog = true}) async {
  return await _seatManager?.leaveSeat(showDialog: showDialog) ?? false;
}
```







