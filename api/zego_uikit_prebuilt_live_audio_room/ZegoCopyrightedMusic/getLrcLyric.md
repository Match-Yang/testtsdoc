


# getLrcLyric method








Future&lt;[ZegoCopyrightedMusicGetLrcLyricResult](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetLrcLyricResult-class.md)> getLrcLyric
(String songID)





<p>Get lyrics in lrc format.</p>
<p>Available since: 2.13.0
Description: Get lyrics in lrc format, support parsing lyrics line by line.
Use case: Used to display lyrics line by line.
When to call: After initializing the copyrighted music success <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md">initCopyrightedMusic</a>.</p>
<ul>
<li><code>songID</code> the ID of the song or accompaniment, the song and accompaniment of a song share the same ID.</li>
</ul>



## Implementation

```dart
Future<ZegoCopyrightedMusicGetLrcLyricResult> getLrcLyric(String songID);
```







