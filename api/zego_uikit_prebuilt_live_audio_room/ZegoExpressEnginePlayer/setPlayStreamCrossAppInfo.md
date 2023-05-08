


# setPlayStreamCrossAppInfo method








Future&lt;void> setPlayStreamCrossAppInfo
(String streamID, [ZegoCrossAppInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoCrossAppInfo-class.md) info)





<p>Set up cross App playing stream information.</p>
<p>Available since: 2.19.0
Description: This information is used for authentication before playing a stream or when retrying playing a stream.
Use cases: Used in scenarios that playing streams across apps.
When to call: after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, after the play stream can be changed at any time.
Restrictions: This function is only valid when playing stream from Zego RTC server.
Caution: Calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/stopPlayingStream.md">stopPlayingStream</a> or <code>logoutRoom</code> will clear this information.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>info</code> Information for cross App playing stream.</li>
</ul>



## Implementation

```dart
Future<void> setPlayStreamCrossAppInfo(
    String streamID, ZegoCrossAppInfo info) async {
  return await ZegoExpressImpl.instance
      .setPlayStreamCrossAppInfo(streamID, info);
}
```







