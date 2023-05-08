


# requestResource method








Future&lt;[ZegoCopyrightedMusicRequestResourceResult](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestResourceResult-class.md)> requestResource
([ZegoCopyrightedMusicRequestConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestConfig-class.md) config, [ZegoCopyrightedMusicResourceType](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicResourceType.md) type)





<p>Request music resource.</p>
<p>Available since: 3.1.0
Description: In addition to obtaining the basic information of the song (duration, song name, singer, etc.), and the most important resource id that can be used for local playback, there are also some related authentications information.
Use case: Get copyrighted songs for local playback and sharing.
Related APIs: After a user in the room successfully calls this interface to request a music resource, other users in the room can call the <code>getsharedresource</code> interface to get the music resource for free once.
When to call: After initializing the copyrighted music <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md">initCopyrightedMusic</a>.
Restrictions: This interface will trigger billing. Each resource has a unique resource ID.</p>
<ul>
<li><code>config</code> The configuration of requesting music resource.</li>
<li><code>type</code> The resource type of music.</li>
<li>Returns Result of requesting music resource.</li>
</ul>



## Implementation

```dart
Future<ZegoCopyrightedMusicRequestResourceResult> requestResource(
    ZegoCopyrightedMusicRequestConfig config,
    ZegoCopyrightedMusicResourceType type);
```







