


# MixerNoOutputTarget constant







int const MixerNoOutputTarget
  




<p>Description: Illegal parameters exist in mixing task configuration. <br>Cause: 1. The mixing task ID is empty; 2. The mixing room ID is empty; 3. The mixing custom data length exceeds 1000 bytes; 4. The mixing output target stream is empty. <br>Solutions: Please check the configuration parameters of the mixing task.</p>



## Implementation

```dart
static const int MixerNoOutputTarget = 1005005;
```







