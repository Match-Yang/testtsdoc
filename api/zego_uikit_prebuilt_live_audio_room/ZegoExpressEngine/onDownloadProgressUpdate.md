


# onDownloadProgressUpdate property







(void Function([ZegoCopyrightedMusic](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic-class.md) copyrightedMusic, String resourceID, double progressRate)?) onDownloadProgressUpdate
  
_<span class="feature">read / write</span>_



<p>Callback for download song or accompaniment progress rate.</p>
<ul>
<li><code>copyrightedMusic</code> Copyrighted music instance that triggers this callback.</li>
<li><code>resourceID</code> The resource ID of the song or accompaniment that triggered this callback.</li>
<li><code>progressRate</code> download progress rate.</li>
</ul>



## Implementation

```dart
static void Function(ZegoCopyrightedMusic copyrightedMusic, String resourceID,
    double progressRate)? onDownloadProgressUpdate;
```







