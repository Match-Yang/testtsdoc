


# avTimestampDiff property







int avTimestampDiff
  
_<span class="feature">read / write</span>_



<p>The difference between the video timestamp and the audio timestamp, used to reflect the synchronization of audio and video, in milliseconds. This value is less than 0 means the number of milliseconds that the video leads the audio, greater than 0 means the number of milliseconds that the video lags the audio, and 0 means no difference. When the absolute value is less than 200, it can basically be regarded as synchronized audio and video, when the absolute value is greater than 200 for 10 consecutive seconds, it can be regarded as abnormal (Available since 1.19.0)</p>



## Implementation

```dart
int avTimestampDiff;
```







