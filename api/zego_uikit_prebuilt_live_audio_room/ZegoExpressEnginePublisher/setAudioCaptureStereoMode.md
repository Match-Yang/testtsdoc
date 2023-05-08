


# setAudioCaptureStereoMode method








Future&lt;void> setAudioCaptureStereoMode
([ZegoAudioCaptureStereoMode](../../zego_uikit_prebuilt_live_audio_room/ZegoAudioCaptureStereoMode.md) mode)





<p>Set audio capture stereo mode.</p>
<p>Available since: 1.15.0 (iOS/Android/Windows); support macOS since 2.16.0
Description: This function is used to set the audio capture channel mode. When the developer turns on the stereo capture, using a special stereo capture device, the stereo audio data can be captured and streamed.
Use cases: In some professional scenes, users are particularly sensitive to sound effects, such as voice radio and musical instrument performance. At this time, support for stereo and high-quality sound is required.
Default value: The default is None, which means mono capture.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>， before <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a>, <code>startPlayingStream</code>, <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPreview.md">startPreview</a>, <code>createMediaPlayer</code>, <code>createAudioEffectPlayer</code> and <code>createRealTimeSequentialDataManager</code>.
Restrictions: If you need to enable stereo capture, you also need to meet the following conditions: For iOS/Android, you need to connect an external audio device that supports stereo capture and be at the media volume. For macOS, it needs to be at the media volume. For Windows, an external audio device that supports stereo capture is required.
Related APIs: When streaming, you need to enable the stereo audio encoding function through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setAudioConfig.md">setAudioConfig</a> interface at the same time.</p>
<ul>
<li><code>mode</code> Audio stereo capture mode.</li>
</ul>



## Implementation

```dart
Future<void> setAudioCaptureStereoMode(
    ZegoAudioCaptureStereoMode mode) async {
  return await ZegoExpressImpl.instance.setAudioCaptureStereoMode(mode);
}
```







