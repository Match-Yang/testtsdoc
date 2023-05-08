


# openSeats method








Future&lt;bool> openSeats
()





<p>打开座位
打开座位后，所有观众都可以自由选择空的seat坐上去开始跟其他人聊天</p>



## Implementation

```dart
Future<bool> openSeats() async {
  return await _seatManager?.lockSeat(false) ?? false;
}
```







