


# enableAccurateSeek method








Future&lt;void> enableAccurateSeek
(bool enable, [ZegoAccurateSeekConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoAccurateSeekConfig-class.md) config)





<p>Enable accurate seek and set relevant attributes.</p>
<p>Available since: 2.4.0
Description: The timestamp specified by normal seek may not an I frame, and then returns the I frame near the specified timestamp, which is not so accurate. But the accurate seek, when the specified timestamp is not an I frame, it will use the I frame near the specified timestamp to decode the frame of the specified timestamp.
Use cases: When user needs to seek to the specified timestamp accurately.
When to call: The setting must be called before <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoMediaPlayer/loadResource.md">loadResource</a>, and it will take effect during the entire life cycle of the media player.</p>
<ul>
<li><code>enable</code> Whether to enable accurate seek</li>
<li><code>config</code> The property setting of accurate seek, only valid when enable is true.</li>
</ul>



## Implementation

```dart
Future<void> enableAccurateSeek(bool enable, ZegoAccurateSeekConfig config);
```







