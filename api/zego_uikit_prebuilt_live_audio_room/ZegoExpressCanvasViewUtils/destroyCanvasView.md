


# destroyCanvasView method








Future&lt;bool> destroyCanvasView
(int viewID)





<p>Destroy a canvas view.</p>
<p>When you no longer need to use a canvas view, you need to call
this function to destroy it to release resources,
otherwise it will cause memory leaks.</p>
<p>If it returns false, it's probably because the canvas view
(in native or web side) to be destroyed doesn't exist or
the ZegoExpressEngine instance is not created.</p>
<p>The <code>viewID</code> is the id of the corresponding canvas view,
which can be obtained from the <code>onViewCreated</code> callback of
the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressCanvasViewUtils/createCanvasView.md">createCanvasView</a> function.</p>



## Implementation

```dart
Future<bool> destroyCanvasView(int viewID) async {
  return await ZegoExpressCanvasViewImpl.destroyCanvasView(viewID);
}
```







