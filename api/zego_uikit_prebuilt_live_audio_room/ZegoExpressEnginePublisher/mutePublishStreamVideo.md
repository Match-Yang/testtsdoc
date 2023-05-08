


# mutePublishStreamVideo method








Future&lt;void> mutePublishStreamVideo
(bool mute, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Stops or resumes sending the video part of a stream for the specified channel.</p>
<p>Available since: 1.1.0
Description: This function can be called when publishing the stream to realize not publishing the video stream. The local camera can still work normally, can capture, preview and process video images normally, but does not send the video data to the network.
When to call: Called after the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> can take effect.
Restrictions: None.
Related callbacks: If you stop sending video streams locally, the remote user that play stream of local user publishing stream can receive <code>Mute</code> status change notification by monitoring <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRemoteCameraStateUpdate.md">onRemoteCameraStateUpdate</a> callbacks.
Related APIs: <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/mutePublishStreamAudio.md">mutePublishStreamAudio</a>.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>mute</code> Whether to stop sending video streams, true means not to send video stream, and false means sending video stream. The default is false.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> mutePublishStreamVideo(bool mute,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .mutePublishStreamVideo(mute, channel: channel);
}
```







