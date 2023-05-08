


# mutePublishStreamAudio method








Future&lt;void> mutePublishStreamAudio
(bool mute, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Stops or resumes sending the audio part of a stream for the specified channel.</p>
<p>Available since: 1.1.0
Description: This function can be called when publishing the stream to realize not publishing the audio data stream. The SDK still collects and processes the audio, but send muted audio frame packets to the network.
When to call: Called after the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> can take effect.
Restrictions: None.
Related callbacks: If you stop sending audio streams, the remote user that play stream of local user publishing stream can receive <code>Mute</code> status change notification by monitoring <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteMicStateUpdate.md">onRemoteMicStateUpdate</a> callbacks.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/mutePublishStreamVideo.md">mutePublishStreamVideo</a>.</p>
<ul>
<li><code>mute</code> Whether to stop sending audio streams, true means not to send audio stream, and false means sending audio stream. The default is false.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> mutePublishStreamAudio(bool mute,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .mutePublishStreamAudio(mute, channel: channel);
}
```







