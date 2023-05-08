


# getMixAudioVideoViewNotifier method








ValueNotifier&lt;Widget?> getMixAudioVideoViewNotifier
(String mixerID)








## Implementation

```dart
ValueNotifier<Widget?> getMixAudioVideoViewNotifier(String mixerID) {
  return ZegoUIKitCore.shared.coreData.mixerStreamDic[mixerID]?.view ??
      ValueNotifier(null);
}
```







