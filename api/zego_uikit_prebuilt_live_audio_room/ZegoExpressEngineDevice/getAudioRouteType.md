


# getAudioRouteType method








Future&lt;[ZegoAudioRoute](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioRoute.md)> getAudioRouteType
()





<p>get current audio route type.</p>
<p>Available since: 1.1.0
Description: Audio routing refers to the audio output device that an app uses to play audio, and common audio routes are: speakers, handsets, headphones, Bluetooth devices, and so on.
When to call: After creating the engine <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Related APIs: Set audio route to speaker <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineDevice/setAudioRouteToSpeaker.md">setAudioRouteToSpeaker</a>.</p>



## Implementation

```dart
Future<ZegoAudioRoute> getAudioRouteType() async {
  return await ZegoExpressImpl.instance.getAudioRouteType();
}
```







