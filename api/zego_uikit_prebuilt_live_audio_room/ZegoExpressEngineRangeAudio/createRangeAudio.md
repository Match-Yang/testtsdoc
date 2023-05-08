


# createRangeAudio method








Future&lt;[ZegoRangeAudio](../../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio-class.md)?> createRangeAudio
()





<p>Creates a range audio instance.</p>
<p>Available since: 2.11.0
Description: Creates a range audio instance.
Use case: Often used in game voice scenarios, users can use related functions by creating range audio instance objects.
When to call: It can be called after the engine by <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> has been initialized.
Restrictions: Currently, a maximum of 1 instances can be created, after which it will return null.
Impacts on other APIs: If you use the range audio module, you cannot use the basic push-pull stream <code>startPublishingStream</code>, <code>startPlayingStream</code> interfaces and related callbacks.</p>
<ul>
<li>Returns range audio instance, null will be returned when the maximum number is exceeded.</li>
</ul>



## Implementation

```dart
Future<ZegoRangeAudio?> createRangeAudio() async {
  return await ZegoExpressImpl.instance.createRangeAudio();
}
```







