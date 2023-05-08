


# initCopyrightedMusic method








Future&lt;[ZegoCopyrightedMusicInitResult](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicInitResult-class.md)> initCopyrightedMusic
([ZegoCopyrightedMusicConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicConfig-class.md) config)





<p>Initialize the copyrighted music module.</p>
<p>Available since: 2.13.0
Description: Initialize the copyrighted music so that you can use the function of the copyrighted music later.
When to call: After initializing the copyrighted music <code>createCopyrightedMusic</code>.
Caution: 1. The real user information must be passed in, otherwise the song resources cannot be obtained for playback. 2. The user ID set when initializing copyrighted music needs to be the same as the user ID set when logging in to the room.</p>
<ul>
<li><code>config</code> the copyrighted music configuration.</li>
</ul>



## Implementation

```dart
Future<ZegoCopyrightedMusicInitResult> initCopyrightedMusic(
    ZegoCopyrightedMusicConfig config);
```







