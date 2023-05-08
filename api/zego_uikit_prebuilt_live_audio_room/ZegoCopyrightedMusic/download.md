


# download method








Future&lt;[ZegoCopyrightedMusicDownloadResult](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicDownloadResult-class.md)> download
(String resourceID)





<p>Download song or accompaniment.</p>
<p>Available since: 2.13.0
Description: Download a song or accompaniment. It can only be played after downloading successfully.
Use case: Get copyrighted accompaniment for local playback and sharing.
When to call: After initializing the copyrighted music success <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md">initCopyrightedMusic</a>.
Caution: Loading songs or accompaniment resources is affected by the network.</p>
<ul>
<li><code>resourceID</code> the resource ID corresponding to the song or accompaniment.</li>
</ul>



## Implementation

```dart
Future<ZegoCopyrightedMusicDownloadResult> download(String resourceID);
```







