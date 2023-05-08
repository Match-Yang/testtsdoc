


# onCapturedDataRecordProgressUpdate property







(void Function([ZegoDataRecordProgress](../../zego_uikit_prebuilt_live_audio_room/ZegoDataRecordProgress-class.md) progress, [ZegoDataRecordConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoDataRecordConfig-class.md) config, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?) onCapturedDataRecordProgressUpdate
  
_<span class="feature">read / write</span>_



<p>The callback to report the current recording progress.</p>
<p>Available since: 1.10.0
Description: Recording progress update callback, triggered at regular intervals during recording.
Use cases: Developers can do UI hints for the user interface.
When to trigger: After <code>startRecordingCapturedData</code> is called, If configured to require a callback, timed trigger during recording.
Restrictions: None.</p>
<ul>
<li><code>progress</code> File recording progress, which allows developers to hint at the UI, etc.</li>
<li><code>config</code> Record config.</li>
<li><code>channel</code> Publishing stream channel.</li>
</ul>



## Implementation

```dart
static void Function(
    ZegoDataRecordProgress progress,
    ZegoDataRecordConfig config,
    ZegoPublishChannel channel)? onCapturedDataRecordProgressUpdate;
```







