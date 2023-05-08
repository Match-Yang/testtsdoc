


# onPlayerMediaEvent property







(void Function(String streamID, [ZegoPlayerMediaEvent](../../zego_uikit_prebuilt_live_audio_room/ZegoPlayerMediaEvent.md) event)?) onPlayerMediaEvent
  
_<span class="feature">read / write</span>_



<p>The callback triggered when a media event occurs during streaming playing.</p>
<p>Available since: 1.1.0
Description: This callback is used to receive pull streaming events.
Use cases: You can use this callback to make statistics on stutters or to make friendly displays in the UI of the app.
When to trigger:  After calling the <code>startPublishingStream</code>, this callback is triggered when an event such as audio and video jamming and recovery occurs in the playing stream.</p>
<ul>
<li><code>streamID</code> Stream ID.</li>
<li><code>event</code> Specific events received when playing the stream.</li>
</ul>



## Implementation

```dart
static void Function(String streamID, ZegoPlayerMediaEvent event)?
    onPlayerMediaEvent;
```







