


# forceSynchronousNetworkTime property







int? forceSynchronousNetworkTime
  
_<span class="feature">read / write</span>_



<p>Whether to synchronize the network time when pushing streams. 1 is synchronized with 0 is not synchronized. And must be used with setStreamAlignmentProperty. It is used to align multiple streams at the mixed stream service or streaming end, such as the chorus scene of KTV.</p>



## Implementation

```dart
int? forceSynchronousNetworkTime;
```







