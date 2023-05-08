


# MixerStopQpsOverload constant







int const MixerStopQpsOverload
  




<p>Description: Stop stream mixing tasks too frequently. <br>Cause: Requests are too frequent, exceeding the qps limit of the service. <br>Solutions: Please ensure that the qps of the stop mixing request is less than 100.</p>



## Implementation

```dart
static const int MixerStopQpsOverload = 1005016;
```







