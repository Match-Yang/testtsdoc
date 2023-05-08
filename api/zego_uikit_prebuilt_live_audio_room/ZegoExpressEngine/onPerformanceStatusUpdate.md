


# onPerformanceStatusUpdate property







(void Function([ZegoPerformanceStatus](../../zego_uikit_prebuilt_live_audio_room/ZegoPerformanceStatus-class.md) status)?) onPerformanceStatusUpdate
  
_<span class="feature">read / write</span>_



<p>System performance monitoring callback.</p>
<p>Available since: 1.19.0
Description: System performance monitoring callback. The callback notification period is the value of millisecond parameter set by call <code>startPerformanceMonitor</code>.
Use cases: Monitor system performance can help user quickly locate and solve performance problems and improve user experience.
When to trigger: It will triggered after <a class="deprecated" href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/createEngine.md">createEngine</a>, and call <code>startPerformanceMonitor</code> to start system performance monitoring.
Restrictions: None.</p>
<ul>
<li><code>status</code> System performance monitoring status.</li>
</ul>



## Implementation

```dart
static void Function(ZegoPerformanceStatus status)? onPerformanceStatusUpdate;
```







