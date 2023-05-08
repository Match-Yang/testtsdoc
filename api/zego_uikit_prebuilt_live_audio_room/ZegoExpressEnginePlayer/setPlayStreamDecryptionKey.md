


# setPlayStreamDecryptionKey method








Future&lt;void> setPlayStreamDecryptionKey
(String streamID, String key)





<p>Set decryption key for the playing stream.</p>
<p>Available since: 1.19.0
Description: When streaming, the audio and video data will be decrypted according to the set key.
Use cases: Usually used in scenarios that require high security for audio and video calls.
When to call: after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, after the play stream can be changed at any time.
Restrictions: This function is only valid when calling from Zego RTC or L3 server.
Related APIs: <code>setPublishStreamEncryptionKey</code>Set the publish stream encryption key.
Caution: This interface can only be called if encryption is set on the publish. Calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePlayer/stopPlayingStream.md">stopPlayingStream</a> or <code>logoutRoom</code> will clear the decryption key.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>key</code> The decryption key, note that the key length only supports 16/24/32 bytes.</li>
</ul>



## Implementation

```dart
Future<void> setPlayStreamDecryptionKey(String streamID, String key) async {
  return await ZegoExpressImpl.instance
      .setPlayStreamDecryptionKey(streamID, key);
}
```







