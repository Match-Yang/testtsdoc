


# installPlugins method








void installPlugins
(List&lt;[IZegoUIKitPlugin](../../zego_uikit_prebuilt_live_audio_room/IZegoUIKitPlugin-mixin.md)> instances)








## Implementation

```dart
void installPlugins(List<IZegoUIKitPlugin> instances) {
  for (final item in instances) {
    final itemType = item.getPluginType();
    if (plugins[itemType] != null) {
      debugPrint('plugin type:$itemType already exists '
          '(${plugins[itemType].hashCode}), '
          'will update plugin instance ${item.hashCode}');
    }
    plugins[itemType] = item;
  }
}
```







