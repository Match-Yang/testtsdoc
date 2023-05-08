


# onMixerRelayCDNStateUpdate property







(void Function(String taskID, List&lt;[ZegoStreamRelayCDNInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoStreamRelayCDNInfo-class.md)> infoList)?) onMixerRelayCDNStateUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the state of relayed streaming of the mixed stream to CDN changes.</p>
<p>Available since: 1.2.1
Description: The general situation of the mixing task on the ZEGO RTC server will push the output stream to the CDN using the RTMP protocol, and the state change during the push process will be notified from the callback function.
Use cases: It is often used when multiple video images are required to synthesize a video using mixed streaming, such as education, live teacher and student images.
When to trigger: After the developer calls the <code>startMixerTask</code> function to start mixing, when the ZEGO RTC server pushes the output stream to the CDN, there is a state change.
Restrictions: None.
Related callbacks: Develop can get the sound update notification of each single stream in the mixed stream through <code>OnMixerSoundLevelUpdate</code>.
Related APIs: Develop can start a mixed flow task through <code>startMixerTask</code>.</p>
<ul>
<li><code>taskID</code> The mixing task ID. Value range: the length does not exceed 256. Caution: This parameter is in string format and cannot contain URL keywords, such as 'http' and '?' etc., otherwise the push and pull flow will fail. Only supports numbers, English characters and'~','!','@','$','%','^','&amp;','*','(',')','_' ,'+','=','-','`',';',''',',','.','&lt;','&gt;','/',''.</li>
<li><code>infoList</code> List of information that the current CDN is being mixed.</li>
</ul>



## Implementation

```dart
static void Function(String taskID, List<ZegoStreamRelayCDNInfo> infoList)?
    onMixerRelayCDNStateUpdate;
```







