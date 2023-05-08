


# text property









String text
  







## Implementation

```dart
String get text {
  final mapValues = {
    BeautyEffectType.whiten: 'Skin Tone',
    BeautyEffectType.rosy: 'Blusher',
    BeautyEffectType.smooth: 'Smoothing',
    BeautyEffectType.sharpen: 'Sharpening',
    BeautyEffectType.none: 'None',
  };

  return mapValues[this]!;
}
```








