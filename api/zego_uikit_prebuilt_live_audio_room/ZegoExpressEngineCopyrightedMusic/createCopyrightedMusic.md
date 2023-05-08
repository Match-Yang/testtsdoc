


# createCopyrightedMusic method








Future&lt;[ZegoCopyrightedMusic](../../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic-class.md)?> createCopyrightedMusic
()





<p>Creates a copyrighted music instance.</p>
<p>Available since: 2.13.0
Description: Creates a copyrighted music instance.
Use case: Often used in online KTV chorus scenarios, users can use related functions by creating copyrighted music instance objects.
When to call: It can be called after the engine by <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> has been initialized.
Restrictions: The SDK only supports the creation of one instance of CopyrightedMusic. Multiple calls to this function return the same object.</p>
<ul>
<li>Returns copyrighted music instance, multiple calls to this function return the same object.</li>
</ul>



## Implementation

```dart
Future<ZegoCopyrightedMusic?> createCopyrightedMusic() async {
  return await ZegoExpressImpl.instance.createCopyrightedMusic();
}
```







