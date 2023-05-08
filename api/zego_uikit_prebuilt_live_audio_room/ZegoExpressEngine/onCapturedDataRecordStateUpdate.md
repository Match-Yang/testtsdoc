


# onCapturedDataRecordStateUpdate property







(void Function([ZegoDataRecordState](../../zego_uikit_prebuilt_live_audio_room/ZegoDataRecordState.md) state, int errorCode, [ZegoDataRecordConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoDataRecordConfig-class.md) config, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)?) onCapturedDataRecordStateUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the state of data recording (to a file) changes.</p>
<p>Available since: 1.10.0
Description: The callback triggered when the state of data recording (to a file) changes.
Use cases: The developer should use this callback to determine the status of the file recording or for UI prompting.
When to trigger: After <code>startRecordingCapturedData</code> is called, if the state of the recording process changes, this callback will be triggered.
Restrictions: None.</p>
<ul>
<li><code>state</code> File recording status.</li>
<li><code>errorCode</code> Error code, please refer to the error codes document <a href="https://docs.zegocloud.com/en/5548.html">https://docs.zegocloud.com/en/5548.html</a> for details.</li>
<li><code>config</code> Record config.</li>
<li><code>channel</code> Publishing stream channel.</li>
</ul>



## Implementation

```dart
static void Function(
    ZegoDataRecordState state,
    int errorCode,
    ZegoDataRecordConfig config,
    ZegoPublishChannel channel)? onCapturedDataRecordStateUpdate;
```







