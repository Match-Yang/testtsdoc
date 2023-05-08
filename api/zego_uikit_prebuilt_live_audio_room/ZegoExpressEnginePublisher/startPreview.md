


# startPreview method








Future&lt;void> startPreview
({[ZegoCanvas](../../zego_uikit_prebuilt_live_audio_room/ZegoCanvas-class.md)? canvas, [ZegoPublishChannel](../../zego_uikit_prebuilt_live_audio_room/ZegoPublishChannel.md)? channel})





<p>Starts/Updates the local video preview (for the specified channel).</p>
<p>Available since: 1.1.0
Description: The user can see his own local image by calling this function.
Use cases: It can be used for local preview in real-time connecting wheat, live broadcast and other scenarios.
When to call: After <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Caution: 1. The preview function does not require you to log in to the room or publish the stream first. But after exiting the room, SDK internally actively stops previewing by default. 2. Local view and preview modes can be updated by calling this function again. The user can only preview on one view. If you call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/startPreview.md">startPreview</a> again to pass in a new view, the preview screen will only be displayed in the new view. 3. You can set the mirror mode of the preview by calling the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEnginePublisher/setVideoMirrorMode.md">setVideoMirrorMode</a> function. The default preview setting is image mirrored. 4. When this function is called, the audio and video engine module inside SDK will start really, and it will start to try to collect audio and video..
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li><code>canvas</code> The view used to display the preview image. If the view is set to null, no preview will be made.</li>
<li><code>channel</code> Publish stream channel</li>
</ul>



## Implementation

```dart
Future<void> startPreview(
    {ZegoCanvas? canvas, ZegoPublishChannel? channel}) async {
  return await ZegoExpressImpl.instance
      .startPreview(canvas: canvas, channel: channel);
}
```







