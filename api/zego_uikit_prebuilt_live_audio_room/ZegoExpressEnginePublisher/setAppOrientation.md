


# setAppOrientation method








Future&lt;void> setAppOrientation
(DeviceOrientation orientation, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Sets the video orientation (for the specified channel).</p>
<p>Available since: 1.1.0
Description: Set the video orientation.
Use cases: When users use mobile devices to conduct live broadcasts or video calls, they can set different video directions according to the scene.
When to call: After <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>orientation</code> Video orientation.</li>
<li><code>channel</code> Publish stream channel.</li>
</ul>



## Implementation

```dart
Future<void> setAppOrientation(DeviceOrientation orientation,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setAppOrientation(orientation, channel: channel);
}
```







