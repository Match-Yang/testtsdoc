


# setDummyCaptureImagePath method








Future&lt;void> setDummyCaptureImagePath
(String filePath, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md) channel)





<p>Set the path of the static picture would be published when the camera is closed.</p>
<p>Available: since 2.9.0
Description: Set the path of the static picture would be published when enableCamera(false) is called, it would start to publish static pictures, and when enableCamera(true) is called, it would end publishing static pictures.
Use case: The developer wants to display a static picture when the camera is closed. For example, when the anchor exits the background, the camera would be actively closed. At this time, the audience side needs to display the image of the anchor temporarily leaving.
When to call: After the engine is initialized, call this API to configure the parameters before closing the camera.
Restrictions:</p>
<ol>
<li>Supported picture types are JPEG/JPG, PNG, BMP, HEIF.</li>
<li>The function is only for SDK video capture and does not take effect for custom video capture.</li>
<li>Not supported that the filePath is a network link.
Caution:</li>
<li>The static picture cannot be seen in the local preview.</li>
<li>External filters, mirroring, watermarks, and snapshots are all invalid.</li>
<li>If the picture aspect ratio is inconsistent with the set code aspect ratio, it will be cropped according to the code aspect ratio.
Platform differences:</li>
<li>Windows: Fill in the location of the picture directly, such as "D://dir//image.jpg".</li>
<li>iOS: If it is a full path, add the prefix "file:", such as @"file:/var/image.png"; If it is a assets picture path, add the prefix "asset:", such as @"asset:watermark".</li>
<li>Android: If it is a full path, add the prefix "file:", such as "file:/sdcard/image.png"; If it is a assets directory path, add the prefix "asset:", such as "asset:watermark.png".</li>
</ol>
<ul>
<li><code>filePath</code> Picture file path</li>
<li><code>channel</code> Publish channel.</li>
</ul>



## Implementation

```dart
Future<void> setDummyCaptureImagePath(
    String filePath, ZegoPublishChannel channel) async {
  return await ZegoExpressImpl.instance
      .setDummyCaptureImagePath(filePath, channel);
}
```







