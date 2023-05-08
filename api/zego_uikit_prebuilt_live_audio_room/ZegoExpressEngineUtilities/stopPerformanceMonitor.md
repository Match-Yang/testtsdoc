


# stopPerformanceMonitor method








Future&lt;void> stopPerformanceMonitor
()





<p>Stop system performance monitoring.</p>
<p>Available since: 1.19.0
Description: Stop system performance monitoring. After the monitoring is stopped, the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPerformanceStatusUpdate.md">onPerformanceStatusUpdate</a> callback will not triggered.
Use cases: Monitor system performance can help user quickly locate and solve performance problems and improve user experience.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Related APIs: Call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineUtilities/startPerformanceMonitor.md">startPerformanceMonitor</a> to start system performance monitoring.</p>



## Implementation

```dart
Future<void> stopPerformanceMonitor() async {
  return await ZegoExpressImpl.instance.stopPerformanceMonitor();
}
```







