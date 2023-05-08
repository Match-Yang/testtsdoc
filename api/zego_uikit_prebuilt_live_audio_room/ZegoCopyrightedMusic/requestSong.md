


# requestSong method







- @Deprecated(&#39;Deprecated since 3.0.2, please use the [requestResource] function instead.&#39;)

Future&lt;[ZegoCopyrightedMusicRequestSongResult](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestSongResult-class.md)> ~~requestSong~~
([ZegoCopyrightedMusicRequestConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestConfig-class.md) config)





<p><code>Deprecated</code> Request a song. Deprecated since 3.0.2, please use the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/requestResource.md">requestResource</a> function instead.</p>
<p>Available since: 2.13.0
Description: By requesting a song, you can not only obtain basic information about a song (such as duration, song name, and artist), but also obtain the resource ID for local playback, share_token for sharing with others, and related authentication information. Support by the time, by the user monthly, by the room monthly subscription three ways.
Use case: Get copyrighted songs for local playback and sharing.
When to call: After initializing the copyrighted music success <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md">initCopyrightedMusic</a>.
Caution: This interface will trigger billing. A song may have three sound qualities: normal, high-definition, and lossless. Each sound quality has a different resource file, and each resource file has a unique resource ID.</p>
<p>@deprecated Deprecated since 3.0.2, please use the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/requestResource.md">requestResource</a> function instead.</p>
<ul>
<li><code>config</code> request configuration.</li>
</ul>



## Implementation

```dart
@Deprecated(
    'Deprecated since 3.0.2, please use the [requestResource] function instead.')
Future<ZegoCopyrightedMusicRequestSongResult> requestSong(
    ZegoCopyrightedMusicRequestConfig config);
```







