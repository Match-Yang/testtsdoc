


# IMDataTooLong constant







int const IMDataTooLong
  




<p>Description: The input real-time sequential data is too long. <br>Cause: The length of the input data is greater than 4096 bytes. <br>Solution: Check the length of the input data, consider splitting the large data packet into multiple small data and sending it multiple times.</p>



## Implementation

```dart
static const int IMDataTooLong = 1009003;
```







