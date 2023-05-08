


# onEngineStateUpdate property







(void Function([ZegoEngineState](../../zego_uikit_prebuilt_live_audio_room/ZegoEngineState.md) state)?) onEngineStateUpdate
  
_<span class="feature">read / write</span>_



<p>The callback triggered when the audio/video engine state changes.</p>
<p>Available since: 1.1.0
Description: Callback notification of audio/video engine status update. When audio/video functions are enabled, such as preview, push streaming, local media player, audio data observering, etc., the audio/video engine will enter the start state. When you exit the room or disable all audio/video functions , The audio/video engine will enter the stop state.
Trigger: The developer called the relevant function to change the state of the audio and video engine. For example: 1. Called ZegoExpressEngine's <code>startPreview</code>, <code>stopPreview</code>, <code>startPublishingStream</code>, <code>stopPublishingStream</code>, <code>startPlayingStream</code>, <code>stopPlayingStream</code>, <code>startAudioDataObserver</code>, <code>stopAudioDataObserver</code> and other functions. 2. The related functions of MediaPlayer are called. 3. The <code>LogoutRoom</code> function was called. 4. The related functions of RealTimeSequentialDataManager are called.
Restrictions: None.
Caution:</p>
<ol>
<li>When the developer calls <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/destroyEngine.md">destroyEngine</a>, this notification will not be triggered because the resources of the SDK are completely released.</li>
<li>If there is no special need, the developer does not need to pay attention to this callback.</li>
</ol>
<ul>
<li><code>state</code> The audio/video engine state.</li>
</ul>



## Implementation

```dart
static void Function(ZegoEngineState state)? onEngineStateUpdate;
```







