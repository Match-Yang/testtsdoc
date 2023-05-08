


# getMusicByToken method







- @Deprecated(&#39;Deprecated since 3.0.2, please use the [getSharedResource] function instead.&#39;)

Future&lt;[ZegoCopyrightedMusicGetMusicByTokenResult](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetMusicByTokenResult-class.md)> ~~getMusicByToken~~
(String shareToken)





<p><code>Deprecated</code> Get a song or accompaniment. Deprecated since 3.0.2, please use the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getSharedResource.md">getSharedResource</a> function instead.</p>
<p>Available since: 2.13.0
Description: After the user successfully obtains the song/accompaniment/climax clip resource, he can get the corresponding shareToken, share the shareToken with other users, and other users call this interface to obtain the shared music resources.
Use case: In the online KTV scene, after receiving the song or accompaniment token shared by the lead singer, the chorus obtains the corresponding song or accompaniment through this interface, and then plays it on the local end.
When to call: After initializing the copyrighted music success <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md">initCopyrightedMusic</a>.</p>
<p>@deprecated Deprecated since 3.0.2, please use the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getSharedResource.md">getSharedResource</a> function instead.</p>
<ul>
<li><code>shareToken</code> access the corresponding authorization token for a song or accompaniment.</li>
</ul>



## Implementation

```dart
@Deprecated(
    'Deprecated since 3.0.2, please use the [getSharedResource] function instead.')
Future<ZegoCopyrightedMusicGetMusicByTokenResult> getMusicByToken(
    String shareToken);
```







