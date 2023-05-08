


# updateCaptureSource method








Future&lt;void> updateCaptureSource
(int sourceId, [ZegoScreenCaptureSourceType](../../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureSourceType.md) sourceType)





<p>Create the screen capture source</p>
<p>Available: since 3.1.0
Description: Update a screen capture source object based on the provided source ID and source type.
Use cases: It is used when you need to record and share the screen or window.
When to call: It can be called after the engine by <code>createScreenCaptureSource</code> has been initialized.
Restrictions: Only support in Windows/macOS.</p>
<ul>
<li><code>sourceId</code> The specified screen ID or window ID.</li>
<li><code>sourceType</code> The specified screen source type.</li>
</ul>



## Implementation

```dart
Future<void> updateCaptureSource(
    int sourceId, ZegoScreenCaptureSourceType sourceType);
```







