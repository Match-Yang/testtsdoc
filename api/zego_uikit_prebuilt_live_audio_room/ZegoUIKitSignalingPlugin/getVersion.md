


# getVersion method







- @override

Future&lt;String> getVersion
()

_<span class="feature">override</span>_






## Implementation

```dart
@override
Future<String> getVersion() async {
  final zimVersion = await ZIM.getVersion();
  if (Platform.isAndroid || Platform.isIOS) {
    final zpnsVersion = await ZPNs.getVersion();
    return 'zego_uikit_signaling_plugin: 2.1.2; zim:$zimVersion; zpns:$zpnsVersion;';
  } else {
    return 'zego_uikit_signaling_plugin: 2.1.2; zim:$zimVersion;';
  }
}
```







