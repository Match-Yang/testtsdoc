


# getSharedResource method








Future&lt;[ZegoCopyrightedMusicGetSharedResourceResult](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetSharedResourceResult-class.md)> getSharedResource
([ZegoCopyrightedMusicGetSharedConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetSharedConfig-class.md) config, [ZegoCopyrightedMusicResourceType](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicResourceType.md) type)





<p>Get shared music resource.</p>
<p>Available since: 3.1.0
Description: In addition to obtaining the basic information of the song (duration, song name, singer, etc.), and the most important resource id that can be used for local playback, there are also some related authentications information.
Use case: Get copyrighted songs for local playback.
Related APIs: After a user in the room calls the <code>requestresource</code> interface to request a music resource successfully, other users in the room can call this interface to get the music resource for free once.
When to call: After initializing the copyrighted music <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md">initCopyrightedMusic</a>.
Restrictions: Each resource has a unique resource ID.</p>
<ul>
<li><code>config</code> The configuration of getting shared music resource.</li>
<li><code>type</code> The resource type of music.</li>
<li>Returns Result of getting shared music resource.</li>
</ul>



## Implementation

```dart
Future<ZegoCopyrightedMusicGetSharedResourceResult> getSharedResource(
    ZegoCopyrightedMusicGetSharedConfig config,
    ZegoCopyrightedMusicResourceType type);
```







