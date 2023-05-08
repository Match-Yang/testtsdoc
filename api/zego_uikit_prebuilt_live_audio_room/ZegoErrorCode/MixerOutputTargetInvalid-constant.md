


# MixerOutputTargetInvalid constant







int const MixerOutputTargetInvalid
  




<p>Description: Illegal format of mixed stream output target parameter. <br>Cause: When the target of the mixed stream output target is streamID, an illegal character is passed in. <br>Solutions: Please check whether the target of the mixed stream output target is of streamID type, if so, target only support numbers, English characters and '-', '_'.</p>



## Implementation

```dart
static const int MixerOutputTargetInvalid = 1005006;
```







