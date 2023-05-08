


# getTurnOnYourCameraRequestStream method








Stream&lt;String> getTurnOnYourCameraRequestStream
()





<p>protocol: String is 'operator'</p>



## Implementation

```dart
Stream<String> getTurnOnYourCameraRequestStream() {
  return ZegoUIKitCore
      .shared.coreData.turnOnYourCameraRequestStreamCtrl.stream;
}
```







