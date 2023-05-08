


# activeAudioByCallKit method







- @override

void activeAudioByCallKit
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
void activeAudioByCallKit() {
  ZegoSignalingLoggerService.logInfo(
    'active audio by callKit',
    tag: 'signaling',
    subTag: 'callkit',
  );

  ZegoSignalingPluginPlatform.instance.activeAudioByCallKit();
}
```







