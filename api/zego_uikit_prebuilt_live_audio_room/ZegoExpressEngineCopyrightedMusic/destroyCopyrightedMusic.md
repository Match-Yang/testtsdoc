


# destroyCopyrightedMusic method








Future&lt;void> destroyCopyrightedMusic
([ZegoCopyrightedMusic](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic-class.md) copyrightedMusic)





<p>Destroys a copyrighted music instance.</p>
<p>Available since: 2.13.0
Description: Destroys a copyrighted music instance.
When to call: It can be called before the engine by <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/destroyEngine.md">destroyEngine</a></p>
<ul>
<li><code>copyrightedMusic</code> The copyrighted music instance object to be destroyed.</li>
</ul>



## Implementation

```dart
Future<void> destroyCopyrightedMusic(
    ZegoCopyrightedMusic copyrightedMusic) async {
  return await ZegoExpressImpl.instance
      .destroyCopyrightedMusic(copyrightedMusic);
}
```







