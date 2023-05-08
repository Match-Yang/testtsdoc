


# setStreamExtraInfo method








Future&lt;[ZegoPublisherSetStreamExtraInfoResult](../../zego_uikit_prebuilt_live_audio_room/ZegoPublisherSetStreamExtraInfoResult-class.md)> setStreamExtraInfo
(String extraInfo, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sets the extra information of the stream being published for the specified publish channel.</p>
<p>Available since: 1.1.0
Description: Use this function to set the extra info of the stream. The stream extra information is an extra information identifier of the stream ID. Unlike the stream ID, which cannot be modified during the publishing process, the stream extra information can be modified midway through the stream corresponding to the stream ID. Developers can synchronize variable content related to stream IDs based on stream additional information.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, Called before and after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a> can both take effect.
Restrictions: None.
Related callbacks: Users can obtain the execution result of the function through <code>ZegoPublisherSetStreamExtraInfoResult</code> callback.</p>
<ul>
<li><code>extraInfo</code> Stream extra information, a string of up to 1024 characters.</li>
<li><code>channel</code> Publish stream channel.</li>
<li>Returns Set stream extra information execution result notification.</li>
</ul>



## Implementation

```dart
Future<ZegoPublisherSetStreamExtraInfoResult> setStreamExtraInfo(
    String extraInfo,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setStreamExtraInfo(extraInfo, channel: channel);
}
```







