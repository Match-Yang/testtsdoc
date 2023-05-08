


# turnMicrophoneOn method








void turnMicrophoneOn
(bool isOn, {String? userID, bool muteMode = false})





<p>turn on/off microphone</p>



## Implementation

```dart
void turnMicrophoneOn(bool isOn, {String? userID, bool muteMode = false}) {
  ZegoUIKitCore.shared.turnMicrophoneOn(
    userID?.isEmpty ?? true
        ? ZegoUIKitCore.shared.coreData.localUser.id
        : userID!,
    isOn,
    muteMode: muteMode,
  );
}
```







