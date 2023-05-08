


# destroyRangeAudio method








Future&lt;void> destroyRangeAudio
([ZegoRangeAudio](../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio-class.md) rangeAudio)





<p>Destroys a range audio instance.</p>
<p>Available since: 2.11.0
Description: Destroys a range audio instance.</p>
<ul>
<li><code>rangeAudio</code> The range audio instance object to be destroyed.</li>
</ul>



## Implementation

```dart
Future<void> destroyRangeAudio(ZegoRangeAudio rangeAudio) async {
  return await ZegoExpressImpl.instance.destroyRangeAudio(rangeAudio);
}
```







