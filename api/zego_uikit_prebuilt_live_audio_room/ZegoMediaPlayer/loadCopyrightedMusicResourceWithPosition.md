


# loadCopyrightedMusicResourceWithPosition method








Future&lt;[ZegoMediaPlayerLoadResourceResult](../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayerLoadResourceResult-class.md)> loadCopyrightedMusicResourceWithPosition
(String resourceID, int startPosition)





<p>Load copyrighted music resource.</p>
<p>Available: since 2.14.0
Description: Load media resources, and specify the progress, in milliseconds, at which playback begins.
Use case: Developers can load the resource ID of copyrighted music.
When to call: It can be called after the engine by <code>createEngine</code> has been initialized and the media player has been created by <code>createMediaPlayer</code>.
Caution: When <code>startPosition</code> exceeds the total playing time, it will start playing from the beginning.</p>
<ul>
<li><code>resourceID</code> The resource ID obtained from the copyrighted music module.</li>
<li><code>startPosition</code> The progress at which the playback started.</li>
<li>Returns Callback result of loading media resource.</li>
</ul>



## Implementation

```dart
Future<ZegoMediaPlayerLoadResourceResult>
    loadCopyrightedMusicResourceWithPosition(
        String resourceID, int startPosition);
```







