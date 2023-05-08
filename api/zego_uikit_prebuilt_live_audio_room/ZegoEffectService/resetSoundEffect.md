


# resetSoundEffect method








Future&lt;void> resetSoundEffect
()





<p>reset sound effect</p>



## Implementation

```dart
Future<void> resetSoundEffect() async {
  await ZegoExpressEngine.instance.setReverbPreset(ZegoReverbPreset.None);
  await ZegoExpressEngine.instance
      .setVoiceChangerPreset(ZegoVoiceChangerPreset.None);
}
```







