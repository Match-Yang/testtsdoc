


# isVideoEncoderSupported method








Future&lt;int> isVideoEncoderSupported
([ZegoVideoCodecID](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) codecID, {[ZegoVideoCodecBackend](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecBackend.md)? codecBackend})





<p>Whether the specified video encoding type is supported.</p>
<p>Available since: 3.0.0 and above
Description: Whether the specified video encoding is supported depends on the following aspects, whether the hardware model supports hard encoding, whether the performance of the hardware model supports soft encoding, and whether the SDK has the encoding module.
When to call: After creating the engine.
Caution: It is recommended that users call this interface to obtain H.265 encoding support capability before publish stream with H.265 encoding, if not supported, you can use other encodings for publish, such as H.264.On the mobile platform, the SDK only supports H.265 hardware encoding, and it is affected by the model and hardware capabilities. You need to call the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enableHardwareEncoder.md">enableHardwareEncoder</a> function to enable hardware encoding, and then use this function to determine whether H.265 hardware encoding is supported.</p>
<ul>
<li><code>codecID</code> Video codec id. Required: Yes.</li>
<li><code>codecBackend</code> Backend implementation of encoder. Required: Yes.</li>
<li>Returns Whether the specified video encoding format is supported; 0 means not supported, and the encoding format cannot be used for publish stream; 1 means support, you can use this encoding format for publish stream; 2 means not confirmed, it is recommended to call this interface later.</li>
</ul>



## Implementation

```dart
Future<int> isVideoEncoderSupported(ZegoVideoCodecID codecID,
    {ZegoVideoCodecBackend? codecBackend}) async {
  return await ZegoExpressImpl.instance
      .isVideoEncoderSupported(codecID, codecBackend: codecBackend);
}
```







