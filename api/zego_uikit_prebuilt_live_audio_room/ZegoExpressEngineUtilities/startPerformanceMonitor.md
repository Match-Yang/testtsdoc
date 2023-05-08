


# startPerformanceMonitor method








Future&lt;void> startPerformanceMonitor
({int? millisecond})





<p>Start system performance monitoring.</p>
<p>Available since: 1.19.0
Description: Start system performance monitoring, monitor system or App's CPU usage and memory usage. Support set the monitoring interval.
Use cases: Monitor system performance can help user quickly locate and solve performance problems and improve user experience.
When to call: It needs to be called after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>.
Restrictions: None.
Related callbacks: After starting monitoring, you can receive system performance status via <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPerformanceStatusUpdate.md">onPerformanceStatusUpdate</a> callback. <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onPerformanceStatusUpdate.md">onPerformanceStatusUpdate</a> callback notification period is the value set by millisecond parameter.
Related APIs: Call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngineUtilities/stopPerformanceMonitor.md">stopPerformanceMonitor</a> to stop system performance monitoring.</p>
<ul>
<li><code>millisecond</code> Monitoring time period(in milliseconds), the value range is <code>1000, 10000</code>. Default value is 2000 ms.</li>
</ul>



## Implementation

```dart
Future<void> startPerformanceMonitor({int? millisecond}) async {
  return await ZegoExpressImpl.instance
      .startPerformanceMonitor(millisecond: millisecond);
}
```







