


# createCanvasView method








Future&lt;Widget?> createCanvasView
(dynamic onViewCreated(int viewID), {Key? key})





<p>Create a canvas view.</p>
<p>When you need to render local preview video through <code>startPreview</code>,
or render remote playing stream's video through <code>startPlayingStream</code>,
you need to call this function to create a canvas view first.</p>
<p>This function will create a canvas view (actully a <code>PlatformView</code> or
a <code>ExternalTexture</code> in native (or web) side), and return a corresponding
flutter widget which can be added into the flutter render tree.</p>
<p>You should also listen to the <code>onViewCreated</code> callback, which will be
called back when the canvas view has been created, then you can use
the <code>viewID</code> to create a <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoCanvas-class.md">ZegoCanvas</a> object for video rendering.</p>



## Implementation

```dart
Future<Widget?> createCanvasView(Function(int viewID) onViewCreated,
    {Key? key}) async {
  return await ZegoExpressCanvasViewImpl.createCanvasView(onViewCreated,
      key: key);
}
```







