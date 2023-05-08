


# DeviceSouldLevelIntervalInvalid constant







int const DeviceSouldLevelIntervalInvalid
  




<p>Description: The set sound level monitoring interval is out of range.<br>Cause: The set sound level monitoring interval is less than 100 milliseconds, or greater than 3000 milliseconds.<br>Solutions: Reset the effective sound level monitoring interval, the effective sound level monitoring interval is <code>100, 3000</code>, in milliseconds.</p>



## Implementation

```dart
static const int DeviceSouldLevelIntervalInvalid = 1006031;
```







