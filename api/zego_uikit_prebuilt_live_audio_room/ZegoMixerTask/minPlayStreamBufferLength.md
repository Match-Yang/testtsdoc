


# minPlayStreamBufferLength property







int minPlayStreamBufferLength
  
_<span class="feature">read / write</span>_



<p>Sets the lower limit of the interval range for the adaptive adjustment of the stream playing cache of the stream mixing server. In the real-time chorus KTV scenario, slight fluctuations in the network at the push end may cause the mixed stream to freeze. At this time, when the audience pulls the mixed stream, there is a high probability of the problem of freeze. By adjusting the lower limit of the interval range for the adaptive adjustment of the stream playing cache of the stream mixing server, it can optimize the freezing problem that occurs when playing mixing streams at the player end, but it will increase the delay. It is not set by default, that is, the server uses its own configuration values. It only takes effect for the new input stream setting, and does not take effect for the input stream that has already started mixing.</p>



## Implementation

```dart
int minPlayStreamBufferLength;
```







