


# loadResource method








Future&lt;[ZegoMediaPlayerLoadResourceResult](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerLoadResourceResult-class.md)> loadResource
(String path)





<p>Load media resource.</p>
<p>Available: since 1.3.4
Description: Load media resources.
Use case: Developers can load the absolute path to the local resource or the URL of the network resource incoming.
When to call: It can be called after the engine by <code>createEngine</code> has been initialized and the media player has been created by <code>createMediaPlayer</code>.
Related APIs: Resources can be loaded through the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadResourceWithPosition.md">loadResourceWithPosition</a> or <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadResourceFromMediaData.md">loadResourceFromMediaData</a> function.</p>
<ul>
<li><code>path</code> The absolute resource path or the URL of the network resource and cannot be null or "". Android can set this path string with Uri.</li>
<li>Returns Callback result of loading media resource.</li>
</ul>



## Implementation

```dart
Future<ZegoMediaPlayerLoadResourceResult> loadResource(String path);
```







