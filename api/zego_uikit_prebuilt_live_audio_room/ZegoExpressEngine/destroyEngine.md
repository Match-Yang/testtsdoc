


# destroyEngine method








Future&lt;void> destroyEngine
()





<p>Destroy the ZegoExpressEngine singleton object and deinitialize the SDK.</p>
<p>Available since: 1.1.0
Description: Destroy the ZegoExpressEngine singleton object and deinitialize the SDK.
When to call: When the SDK is no longer used, the resources used by the SDK can be released through this interface
Restrictions: None.
Caution: After using <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a> to create a singleton, if the singleton object has not been created or has been destroyed, you will not receive related callbacks when calling this function.</p>



## Implementation

```dart
static Future<void> destroyEngine() async {
  return await ZegoExpressImpl.destroyEngine();
}
```







