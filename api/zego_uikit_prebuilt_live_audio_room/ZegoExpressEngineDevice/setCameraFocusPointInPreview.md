


# setCameraFocusPointInPreview method








Future&lt;void> setCameraFocusPointInPreview
(double x, double y, {[ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Set the focus point in the preview view.</p>
<p>Available since: 2.14.0
Description: Set the focus point in the preview view. (x, y) are the normalized coordinates in the preview view, that is, the ratio of the position of the focus point relative to the preview view and the width and height of the preview view. The upper left corner is (0, 0).
Trigger: Called after turn on preview <code>startPreivew</code>.
Restrictions: Currently only supports iOS and Android platforms.
Caution: Every time the camera restarts the acquisition, the settings will become invalid and need to be reset.
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>x</code> Normalized X axis coordinate value, effective value <code>0,1</code>.</li>
<li><code>y</code> Normalized Y axis coordinate value, effective value <code>0,1</code>.</li>
<li><code>channel</code> Publishing stream channel</li>
</ul>



## Implementation

```dart
Future<void> setCameraFocusPointInPreview(double x, double y,
    {ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .setCameraFocusPointInPreview(x, y, channel: channel);
}
```







