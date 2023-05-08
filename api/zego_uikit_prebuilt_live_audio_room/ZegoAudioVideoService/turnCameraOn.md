


# turnCameraOn method








void turnCameraOn
(bool isOn, {String? userID})





<p>turn on/off camera</p>



## Implementation

```dart
void turnCameraOn(bool isOn, {String? userID}) {
  ZegoUIKitCore.shared.turnCameraOn(
      userID?.isEmpty ?? true
          ? ZegoUIKitCore.shared.coreData.localUser.id
          : userID!,
      isOn);
}
```







