


# closeSeats method








Future&lt;bool> closeSeats
()





<p>关闭座位
关闭后观众要通过向 host 申请才能坐到 seat 上或者 host 主动邀请观众也行</p>



## Implementation

```dart
Future<bool> closeSeats() async {
  return await _seatManager?.lockSeat(true) ?? false;
}
```







