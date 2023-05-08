


# getScreenCaptureSources method








Future&lt;List&lt;[ZegoScreenCaptureSourceInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoScreenCaptureSourceInfo-class.md)>> getScreenCaptureSources
(int thumbnailWidth, int thumbnailHeight, int iconWidth, int iconHeight)





<p>Get a list of screens or windows in a screen.</p>
<p>Available since: 3.1.0
Description: Get a list of screens or windows in a screen.
Restrictions: Only support in Windows/macOS.</p>
<ul>
<li><code>thumbnailWidth</code> Get the thumbnail width corresponding to the window, the thumbnail can be used to draw on the window selection interface. (unit is pixel)</li>
<li><code>thumbnailHeight</code> Get the thumbnail height corresponding to the window, the thumbnail can be used to draw on the window selection interface. (unit is pixel)</li>
<li><code>iconWidth</code> Get the width of the icon corresponding to the program. (unit is pixel)</li>
<li><code>iconHeight</code> Get the height of the icon corresponding to the program. (unit is pixel)</li>
<li>Returns List of capture source info objects.</li>
</ul>



## Implementation

```dart
Future<List<ZegoScreenCaptureSourceInfo>> getScreenCaptureSources(
    int thumbnailWidth,
    int thumbnailHeight,
    int iconWidth,
    int iconHeight) async {
  return await ZegoExpressImpl.instance.getScreenCaptureSources(
      thumbnailWidth, thumbnailHeight, iconWidth, iconHeight);
}
```







