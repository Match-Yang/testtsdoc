


# destroyRealTimeSequentialDataManager method








Future&lt;void> destroyRealTimeSequentialDataManager
([ZegoRealTimeSequentialDataManager](../../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md) manager)





<p>Destroy the real time sequential data manager instance</p>
<p>Available: since 2.14.0
Description: Destroy the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md">ZegoRealTimeSequentialDataManager</a> instance object.
Use cases: When you no longer need to use the real-time signaling function, you can use this function to destroy the instance object created by the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineIM/createRealTimeSequentialDataManager.md">createRealTimeSequentialDataManager</a> function
When to call: When you need to the real-time signaling manager object needs to be destroyed
Restrictions: After destroy the instance, you need to release the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRealTimeSequentialDataManager-class.md">ZegoRealTimeSequentialDataManager</a> instance object you hold by yourself, and don’t call the function of this instance object after the destruction.
Caution: If you have not called <code>enableCamera</code> / <code>enableAudioCaptureDevice</code> before this object is destroyed, the SDK will automatically restore (enable) the camera and microphone after the object is destroyed.</p>
<ul>
<li><code>manager</code> The real time sequential data manager instance to be destroyed.</li>
</ul>



## Implementation

```dart
Future<void> destroyRealTimeSequentialDataManager(
    ZegoRealTimeSequentialDataManager manager) async {
  return await ZegoExpressImpl.instance
      .destroyRealTimeSequentialDataManager(manager);
}
```







