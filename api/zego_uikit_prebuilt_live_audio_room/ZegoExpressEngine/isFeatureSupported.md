


# isFeatureSupported method








Future&lt;bool> isFeatureSupported
([ZegoFeatureType](../../zego_uikit_prebuilt_live_audio_room/ZegoFeatureType.md) featureType)





<p>Query whether the current SDK supports the specified feature.</p>
<p>Available since: 2.22.0
Description:
Since the SDK supports feature trimming, some features may be trimmed;
you can use this function to quickly determine whether the current SDK supports the specified features,
such as querying whether the media player feature is supported.
When to call: Any time.</p>
<ul>
<li><code>featureType</code> Type of feature to query.</li>
<li>Returns Whether the specified feature is supported. true: supported; false: not supported.</li>
</ul>



## Implementation

```dart
static Future<bool> isFeatureSupported(ZegoFeatureType featureType) async {
  return await ZegoExpressImpl.isFeatureSupported(featureType);
}
```







