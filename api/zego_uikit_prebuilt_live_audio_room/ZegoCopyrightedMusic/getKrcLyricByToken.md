


# getKrcLyricByToken method








Future&lt;[ZegoCopyrightedMusicGetKrcLyricByTokenResult](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetKrcLyricByTokenResult-class.md)> getKrcLyricByToken
(String krcToken)





<p>Get lyrics in krc format.</p>
<p>Available since: 2.13.0
Description: Get lyrics in krc format, support parsing lyrics word by word.
Use case: Used to display lyrics word by word.
When to call: After initializing the copyrighted music success <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md">initCopyrightedMusic</a>.</p>
<ul>
<li><code>krcToken</code> The krcToken obtained by calling requestAccompaniment.</li>
</ul>



## Implementation

```dart
Future<ZegoCopyrightedMusicGetKrcLyricByTokenResult> getKrcLyricByToken(
    String krcToken);
```







