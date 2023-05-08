


# takeSeat method








Future&lt;bool> takeSeat
(int index)





<p>让观众占据编号为<code>index</code>的座位
座位编号从0开始，从左往右从上往下递增。</p>



## Implementation

```dart
Future<bool> takeSeat(int index) async {
  return await _seatManager?.takeOnSeat(
        index,
        isForce: true,
        isUpdateOwner: true,
        isDeleteAfterOwnerLeft: true,
      ) ??
      false;
}
```







