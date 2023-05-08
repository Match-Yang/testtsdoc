


# text property









String text
  







## Implementation

```dart
String get text {
  final mapValues = {
    ZegoViewBuilderMapExtraInfoKey.isScreenSharingView:
        'is_screen_sharing_view',
    ZegoViewBuilderMapExtraInfoKey.isFullscreen: 'is_fullscreen',
  };

  return mapValues[this]!;
}
```








