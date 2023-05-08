


# MixerStartQpsOverload constant







int const MixerStartQpsOverload
  




<p>Description: Starts stream mixing tasks too frequently. <br>Cause: Requests are too frequent, exceeding the qps limit of the service. <br>Solutions: Please ensure that the qps of the mixing request is less than 100.</p>



## Implementation

```dart
static const int MixerStartQpsOverload = 1005015;
```







