


# sendExtendedRequest method








Future&lt;[ZegoCopyrightedMusicSendExtendedRequestResult](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicSendExtendedRequestResult-class.md)> sendExtendedRequest
(String command, String params)





<p>Send extended feature request.</p>
<p>Available since: 2.13.0
Description: Initialize the copyrighted music so that you can use the function of the copyrighted music later.
Use case: Used to get a list of songs.
When to call: After initializing the copyrighted music success <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md">initCopyrightedMusic</a>.</p>
<ul>
<li><code>command</code> request command, details about the commands supported.</li>
<li><code>params</code> request parameters, each request command has corresponding request parameters.</li>
</ul>



## Implementation

```dart
Future<ZegoCopyrightedMusicSendExtendedRequestResult> sendExtendedRequest(
    String command, String params);
```







