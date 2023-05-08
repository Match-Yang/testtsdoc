


# getAssetAbsolutePath method








Future&lt;String?> getAssetAbsolutePath
(String assetPath)





<p>Get the actual absolute path of the asset through the relative path of the asset</p>
<ul>
<li><code>assetPath</code> The resource path configured in the <code>flutter</code> -&gt; <code>assets</code> field of pubspec.yaml, for example: assets/icon/setting.png</li>
<li>Returns the actual absolute path of the asset</li>
</ul>



## Implementation

```dart
Future<String?> getAssetAbsolutePath(String assetPath) async {
  return await ZegoExpressImpl.methodChannel
      .invokeMethod('getAssetAbsolutePath', {'assetPath': assetPath});
}
```







