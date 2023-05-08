


# setCameraExposureCompensation method








Future&lt;void> setCameraExposureCompensation
(double value, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Set the camera exposure compensation value.</p>
<p>Available since: 2.10.0
Description: Set the camera exposure compensation value.
Use cases: User can call this function to set the camera exposure compensation value.
When to call /Trigger: Called this function after calling <code>startPublishingStream</code> or <code>startPreview</code>.
Restrictions: None.
Caution: The setting will be invalid when the camera is restarted.
Platform differences: Only supports iOS and Android.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>value</code> Camera exposure, the value range is <code>-1,1</code>, the default 0, -1 tends to darken, 1 tends to brighten.</li>
<li><code>channel</code> Publishing stream channel</li>
</ul>



## Implementation

```dart
Future<void> setCameraExposureCompensation(double value,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setCameraExposureCompensation(value, channel: channel);
}
```







