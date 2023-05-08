


# setVideoSource method








Future&lt;int> setVideoSource
([ZegoVideoSourceType](../../zego_uikit_prebuilt_live_audio_room/ZegoVideoSourceType.md) source, {int? instanceID, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Set a video capture instance as video capture source for the specified channel.</p>
<p>Available since: 3.1.0
Description: Set video capture source for switching between different video capture sources.
Use cases: Typically used in educational scenarios that require switching between different video capture sources.
When to call: After the engine is created <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: Calling in publishing or preview is invalid when using the web platform.
Caution: 1. Main push channel ZegoPublishChannel.Main does not support using ZegoVideoSourceType.Player and ZegoVideoSourceType.MainPublishChannel video source type.
 2. When using ZegoVideoSourceType.Player and ZegoVideoSourceType.MainPublishChannel video source type in aux publish channel ZegoPublishChannel.Aux, must ensure that physical device works on main publish channel ZegoPublishChannel.Main
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>source</code> Video capture source.</li>
<li><code>instanceID</code> Video capture source instance id.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<int> setVideoSource(ZegoVideoSourceType source,
    {int? instanceID, ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setVideoSource(source, instanceID: instanceID, channel: channel);
}
```







