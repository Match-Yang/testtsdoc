


# createScreenCaptureSource method








Future&lt;[ZegoScreenCaptureSource](../../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureSource-class.md)?> createScreenCaptureSource
({int? sourceId, [ZegoScreenCaptureSourceType](../../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureSourceType.md)? sourceType})





<p>Create the screen capture source</p>
<p>Available: since 3.1.0
Description: Creates a screen capture source object based on the provided source ID and source type.
Use cases: It is used when you need to record and share the screen or window.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.</p>
<ul>
<li><code>sourceId</code> The specified screen ID or window ID. Only macOS and windows platforms need to pass in this parameter.</li>
<li><code>sourceType</code> The specified screen source type. Only macOS and windows platforms need to pass in this parameter.</li>
<li>Returns The screen capture instance, null will be returned when the maximum number is exceeded.</li>
</ul>



## Implementation

```dart
Future<ZegoScreenCaptureSource?> createScreenCaptureSource(
    {int? sourceId, ZegoScreenCaptureSourceType? sourceType}) async {
  return await ZegoExpressImpl.instance
      .createScreenCaptureSource(sourceId: sourceId, sourceType: sourceType);
}
```







