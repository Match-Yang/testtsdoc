


# MixerStartRequestError constant







int const MixerStartRequestError
  




<p>Description: Failed to start the stream mixing task. <br>Cause: Requests are too frequent, exceeding the qps limit of the service. <br>Solutions: Please ensure that the qps of the mixing request is less than 100.</p>



## Implementation

```dart
static const int MixerStartRequestError = 1005010;
```







