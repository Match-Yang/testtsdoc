


# requestAccompanimentClip method







- @Deprecated(&#39;Deprecated since 3.0.2, please use the [requestResource] function instead.&#39;)

Future&lt;[ZegoCopyrightedMusicRequestAccompanimentClipResult](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestAccompanimentClipResult-class.md)> ~~requestAccompanimentClip~~
([ZegoCopyrightedMusicRequestConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestConfig-class.md) config)





<p><code>Deprecated</code> Request accompaniment clip. Deprecated since 3.0.2, please use the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/requestResource.md">requestResource</a> function instead.</p>
<p>Available since: 2.13.0
Description: You can get the climax clip resources of the song corresponding to the songID, including resource_id, krc_token, share_token, etc. Supports accompaniment climax clips by pay-per-use.
Use case: Get copyrighted accompaniment clip for local playback and sharing.
When to call: After initializing the copyrighted music success <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md">initCopyrightedMusic</a>.
Caution: This interface will trigger billing.</p>
<p>@deprecated Deprecated since 3.0.2, please use the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/requestResource.md">requestResource</a> function instead.</p>
<ul>
<li><code>config</code> request configuration.</li>
</ul>



## Implementation

```dart
@Deprecated(
    'Deprecated since 3.0.2, please use the [requestResource] function instead.')
Future<ZegoCopyrightedMusicRequestAccompanimentClipResult>
    requestAccompanimentClip(ZegoCopyrightedMusicRequestConfig config);
```







