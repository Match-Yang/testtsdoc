


# setRoomScenario method








Future&lt;void> setRoomScenario
([ZegoScenario](../../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) scenario)





<p>Set room scenario.</p>
<p>Available since: 3.0.0
Description: You can set the scenario of the room, and the SDK will adopt different optimization strategies for different scenarios in order to obtain better effects; this function does exactly the same thing as the <code>scenario</code> parameter in the <code>profile</code> configuration of <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Use cases: This function is suitable for apps in various audio and video business scenarios, such as 1v1 video call (or voice call) scenario and live show scenario; this function can be used to switch scenarios without destroying the engine through <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/destroyEngine.md">destroyEngine</a>.
When to call: Must be set before calling <code>loginRoom</code> AND after calling <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: Once you log in to the room, you are no longer allowed to modify the room scenario. If you need to modify the scenario, you need to log out of the room first. If you log in to multiple rooms, you need to log out of all rooms before you can modify it.
Caution:</p>
<ol>
<li>Users in the same room are recommended to use the same room scenario for best results.</li>
<li>Setting the scenario will affect the audio and video bit rate, frame rate, resolution, codec id, audio device mode, audio route type, traffic control, 3A, ear return and other audio and video configurations. If you have special needs, you can call various other APIs to set the above configuration after calling this API.</li>
<li>Calling this function will override the scenario specified on <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> or the scenario set by the last call to this function.</li>
<li>Calling this function will overwrite the audio and video related configuration you set through APIs such as <code>setVideoConfig</code>, <code>setAudioConfig</code>, so it is recommended to set the scenario first and then adjust the audio and video configuration through other APIs.</li>
</ol>
<ul>
<li><code>scenario</code> Room scenario.</li>
</ul>



## Implementation

```dart
Future<void> setRoomScenario(ZegoScenario scenario) async {
  return await ZegoExpressImpl.instance.setRoomScenario(scenario);
}
```







