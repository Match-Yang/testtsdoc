


# CommonEventHandlerExists constant







int const CommonEventHandlerExists
  




<p>Description: <code>setEventHandler</code> has been called to set the handler, please do not set it repeatedly. <br>Cause: Call <code>setEventHandler</code> repeatedly to set the handler.<br>Solutions: If you need to repeat the settings, please call <code>setEventHandler</code> first to empty the previous handler.</p>



## Implementation

```dart
static const int CommonEventHandlerExists = 1000008;
```







