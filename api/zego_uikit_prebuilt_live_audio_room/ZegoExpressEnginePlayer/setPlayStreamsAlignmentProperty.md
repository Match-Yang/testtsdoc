


# setPlayStreamsAlignmentProperty method








Future&lt;void> setPlayStreamsAlignmentProperty
([ZegoStreamAlignmentMode](../../zego_uikit_prebuilt_live_audio_room/ZegoStreamAlignmentMode.md) mode)





<p>Set the play stream alignment properties.</p>
<p>Available since: 2.14.0
Description: When playing at the streaming end, control whether the playing RTC stream needs to be accurately aligned. If necessary, all the streams that contain precise alignment parameters will be aligned; if not, all streams are not aligned.
Use case: It is often used in scenes that require mixed stream alignment such as KTV to ensure that users can switch between singing anchors, ordinary Maishangyu chat anchors, and Maixia audiences at any time during use.
Default value: If this interface is not called, the default is not aligned.
When to call: Called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>. Call the interface repeatedly, and the latest setting is valid.
Related APIs: Set the precise alignment parameter of the stream channel <code>setStreamAlignmentProperty</code>.</p>
<ul>
<li><code>mode</code> Setting the stream alignment mode.</li>
</ul>



## Implementation

```dart
Future<void> setPlayStreamsAlignmentProperty(
    ZegoStreamAlignmentMode mode) async {
  return await ZegoExpressImpl.instance.setPlayStreamsAlignmentProperty(mode);
}
```







