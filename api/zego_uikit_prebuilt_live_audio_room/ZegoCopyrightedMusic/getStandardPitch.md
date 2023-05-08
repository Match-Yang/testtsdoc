


# getStandardPitch method








Future&lt;[ZegoCopyrightedMusicGetStandardPitchResult](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetStandardPitchResult-class.md)> getStandardPitch
(String resourceID)





<p>Get standard pitch data.</p>
<p>Available since: 2.15.0
Description: Get standard pitch data.
Use case: Can be used to display standard pitch lines on the view.
Cation: Only accompaniment or climactic clip assets have pitch lines.</p>
<ul>
<li><code>resourceID</code> the resource ID corresponding to the accompaniment or accompaniment clip.</li>
</ul>



## Implementation

```dart
Future<ZegoCopyrightedMusicGetStandardPitchResult> getStandardPitch(
    String resourceID);
```







