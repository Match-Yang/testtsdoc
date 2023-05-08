


# loadResourceWithPosition method








Future&lt;[ZegoMediaPlayerLoadResourceResult](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerLoadResourceResult-class.md)> loadResourceWithPosition
(String path, int startPosition)





<p>Load media resource.</p>
<p>Available: since 2.14.0
Description: Load media resources, and specify the progress, in milliseconds, at which playback begins.
Use case: Developers can load the absolute path to the local resource or the URL of the network resource incoming.
When to call: It can be called after the engine by <code>createEngine</code> has been initialized and the media player has been created by <code>createMediaPlayer</code>.
Related APIs: Resources can be loaded through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadResource.md">loadResource</a> or <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadResourceFromMediaData.md">loadResourceFromMediaData</a> function.
Caution: When <code>startPosition</code> exceeds the total playing time, it will start playing from the beginning.</p>
<ul>
<li><code>path</code> The absolute resource path or the URL of the network resource and cannot be null or "". Android can set this path string with Uri.</li>
<li><code>startPosition</code> The progress at which the playback started.</li>
<li>Returns Callback result of loading media resource.</li>
</ul>



## Implementation

```dart
Future<ZegoMediaPlayerLoadResourceResult> loadResourceWithPosition(
    String path, int startPosition);
```







