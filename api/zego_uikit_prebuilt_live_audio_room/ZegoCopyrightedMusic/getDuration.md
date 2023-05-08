


# getDuration method








Future&lt;int> getDuration
(String resourceID)





<p>Get the playing time of a song or accompaniment file.</p>
<p>Available since: 2.13.0
Description: Get the playing time of a song or accompaniment file.
Use case: Can be used to display the playing time information of the song or accompaniment on the view.
When to call: After initializing the copyrighted music success <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md">initCopyrightedMusic</a>.</p>
<ul>
<li><code>resourceID</code> the resource ID corresponding to the song or accompaniment.</li>
</ul>



## Implementation

```dart
Future<int> getDuration(String resourceID);
```







