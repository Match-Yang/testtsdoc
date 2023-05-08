


# samples property







int samples
  
_<span class="feature">read / write</span>_



<p>The number of samples required to encode a frame; if samples = 0, the SDK will use the internal sample number, and the SDK will pass the audio data to the external pre-processing module. If the samples! = 0 (the effective value of samples is between <code>160, 2048</code>), and the SDK will send audio data to the external preprocessing module that sets the length of sample number.</p>



## Implementation

```dart
int samples;
```







