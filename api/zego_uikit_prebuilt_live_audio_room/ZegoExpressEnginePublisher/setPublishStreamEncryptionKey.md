


# setPublishStreamEncryptionKey method








Future&lt;void> setPublishStreamEncryptionKey
(String key, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Set encryption key for the publishing stream for the specified publish channel.</p>
<p>Available since: 1.19.0
Description: Support calling this function to update the encryption key while publishing stream.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, Called before and after <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a> can both take effect.
Restrictions: This function is only valid when publishing stream to the Zego RTC server.
Caution: Note that developers need to update the player's decryption key before updating the publisher's encryption key.
Related APIs: Calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/stopPublishingStream.md">stopPublishingStream</a> or <code>logoutRoom</code> will clear the encryption key.</p>
<ul>
<li><code>key</code> The encryption key, note that the key length only supports 16/24/32 bytes.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> setPublishStreamEncryptionKey(String key,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setPublishStreamEncryptionKey(key, channel: channel);
}
```







