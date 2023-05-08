


# setTrafficControlFocusOn method








Future&lt;void> setTrafficControlFocusOn
([ZegoTrafficControlFocusOnMode](../../zego_uikit_prebuilt_live_audio_room/ZegoTrafficControlFocusOnMode.md) mode, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Set the factors of concern that trigger traffic control for the specified publish channel.</p>
<p>Available since: 2.4.0
Description: Use this interface to control whether to start traffic control due to poor remote network conditions.
Default value: Default is disable.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, Called before <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPublishingStream.md">startPublishingStream</a> can take effect.
Restrictions: The traffic control must be turned on <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/enableTrafficControl.md">enableTrafficControl</a>.
Related APIs: [enableTrafficControl.</p>
<ul>
<li><code>mode</code> When LOCAL_ONLY is selected, only the local network status is concerned. When choosing REMOTE, also take into account the remote network.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> setTrafficControlFocusOn(ZegoTrafficControlFocusOnMode mode,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setTrafficControlFocusOn(mode, channel: channel);
}
```







