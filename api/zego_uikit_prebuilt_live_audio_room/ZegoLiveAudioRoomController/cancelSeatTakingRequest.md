


# cancelSeatTakingRequest method








Future&lt;bool> cancelSeatTakingRequest
()





<p>观众取消请求占座位</p>



## Implementation

```dart
Future<bool> cancelSeatTakingRequest() async {
  return await _connectManager?.audienceCancelTakeSeatRequest() ?? false;
}
```







