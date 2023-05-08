


# IMRepeatSubscribe constant







int const IMRepeatSubscribe
  




<p>Description: Repeat broadcast. <br>Cause: The developer repeatedly calls the <code>startBroadcasting</code> function. <br>Solution: Please check the business logic to avoid repeating the subscribe for the stream which is subscribing.</p>



## Implementation

```dart
static const int IMRepeatSubscribe = 1009038;
```







