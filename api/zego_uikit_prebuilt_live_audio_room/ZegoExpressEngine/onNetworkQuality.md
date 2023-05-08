


# onNetworkQuality property







(void Function(String userID, [ZegoStreamQualityLevel](../../zego_uikit_prebuilt_live_audio_room/ZegoStreamQualityLevel.md) upstreamQuality, [ZegoStreamQualityLevel](../../zego_uikit_prebuilt_live_audio_room/ZegoStreamQualityLevel.md) downstreamQuality)?) onNetworkQuality
  
_<span class="feature">read / write</span>_



<p>The network quality callback of users who are publishing in the room.</p>
<p>Available since: 2.10.0
Description: The uplink and downlink network callbacks of the local and remote users, that would be called by default every two seconds for the local and each playing remote user's network quality.
Versions 2.10.0 to 2.13.1:</p>
<ol>
<li>Developer must both publish and play streams before you receive your own network quality callback.</li>
<li>When playing a stream, the publish end has a play stream and the publish end is in the room where it is located, then the user's network quality will be received.
Version 2.14.0 and above:</li>
<li>As long as you publish or play a stream, you will receive your own network quality callback.</li>
<li>When you play a stream, the publish end is in the room where you are, and you will receive the user's network quality.
Version 2.22.0 and above:</li>
<li>Estimate the network conditions of the remote stream publishing user. If the remote stream publishing user loses one heartbeat, the network quality will be called back as unknown; if the remote stream publishing user's heartbeat loss reaches 3 Second, call back its network quality to die.
Use case: When the developer wants to analyze the network condition on the link, or wants to know the network condition of local and remote users.
When to Trigger: After publishing a stream by called <code>startPublishingStream</code> or playing a stream by called <code>startPlayingStream</code>.</li>
</ol>
<ul>
<li><code>userID</code> User ID, empty means local user</li>
<li><code>upstreamQuality</code> Upstream network quality</li>
<li><code>downstreamQuality</code> Downstream network quality</li>
</ul>



## Implementation

```dart
static void Function(String userID, ZegoStreamQualityLevel upstreamQuality,
    ZegoStreamQualityLevel downstreamQuality)? onNetworkQuality;
```







