


# isVideoDecoderSupported method








Future&lt;int> isVideoDecoderSupported
([ZegoVideoCodecID](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) codecID, {[ZegoVideoCodecBackend](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecBackend.md)? codecBackend})





<p>Whether the specified video decoding format is supported.</p>
<p>Available since: 3.0.0
Description: Whether the specified video decoding is supported depends on the following aspects: whether the hardware model supports hard decoding, whether the performance of the hardware model supports soft decoding, and whether the SDK includes the decoding module.
When to call: After creating the engine.
Caution: It is recommended that users call this interface to obtain the H.265 decoding support capability before pulling the H.265 stream. If it is not supported, the user can pull the stream of other encoding formats, such as H.264.</p>
<ul>
<li><code>codecID</code> Video codec id. Required: Yes.</li>
<li><code>codecBackend</code> Backend implementation of decoder. Required: Yes.</li>
<li>Returns Whether the specified video decoding format is supported; 0 means not supported, and the decoding format cannot be used for play stream; 1 means support, you can use this decoding format for playing stream; 2 means not confirmed, it is recommended to call this interface later.</li>
</ul>



## Implementation

```dart
Future<int> isVideoDecoderSupported(ZegoVideoCodecID codecID,
    {ZegoVideoCodecBackend? codecBackend}) async {
  return await ZegoExpressImpl.instance
      .isVideoDecoderSupported(codecID, codecBackend: codecBackend);
}
```







