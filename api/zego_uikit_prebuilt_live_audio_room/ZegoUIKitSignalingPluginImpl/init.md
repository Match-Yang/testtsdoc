


# init method








Future&lt;void> init
(int appID, {String appSign = ''})





<p>init</p>



## Implementation

```dart
Future<void> init(
  int appID, {
  String appSign = '',
}) async {
  initUserInRoomAttributes();
  return ZegoSignalingPluginCore.shared.init(appID: appID, appSign: appSign);
}
```







