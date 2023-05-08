


# getTurnOnYourMicrophoneRequestStream method








Stream&lt;String> getTurnOnYourMicrophoneRequestStream
()





<p>protocol: String is 'operator'</p>



## Implementation

```dart
Stream<String> getTurnOnYourMicrophoneRequestStream() {
  return ZegoUIKitCore
      .shared.coreData.turnOnYourMicrophoneRequestStreamCtrl.stream;
}
```







