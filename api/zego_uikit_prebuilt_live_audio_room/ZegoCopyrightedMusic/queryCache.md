


# queryCache method








Future&lt;bool> queryCache
(String songID, [ZegoCopyrightedMusicType](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicType.md) type)





<p>Query the resource's cache is existed or not.</p>
<p>Available since: 2.13.0
Description: Query the resource is existed or not.
Use case: Can be used to check the resource's cache is existed or not
When to call: After initializing the copyrighted music success <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md">initCopyrightedMusic</a>.</p>
<ul>
<li><code>songID</code> the ID of the song or accompaniment, the song and accompaniment of a song share the same ID.</li>
<li><code>type</code> the song resource type.</li>
</ul>



## Implementation

```dart
Future<bool> queryCache(String songID, ZegoCopyrightedMusicType type);
```







