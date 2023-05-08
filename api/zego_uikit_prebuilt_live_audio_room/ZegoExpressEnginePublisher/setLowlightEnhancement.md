


# setLowlightEnhancement method








Future&lt;void> setLowlightEnhancement
([ZegoLowlightEnhancementMode](../../zego_uikit_prebuilt_live_audio_room/ZegoLowlightEnhancementMode.md) mode, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Set low light enhancement.</p>
<p>Available since: 2.21.0
Description: According to the set low-light enhancement mode, the brightness of the image captured by the camera is enhanced, which is compatible with the beauty function. Users can watch the effect while previewing and toggle the low-light enhancement mode in real time.
Use cases: The environment on the streaming end is dark, or the frame rate set by the camera is high, which causes the picture to be dark, and the subject cannot be displayed or recognized normally.
Default value: Off.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>mode</code> Low light enhancement mode.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> setLowlightEnhancement(ZegoLowlightEnhancementMode mode,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setLowlightEnhancement(mode, channel: channel);
}
```







