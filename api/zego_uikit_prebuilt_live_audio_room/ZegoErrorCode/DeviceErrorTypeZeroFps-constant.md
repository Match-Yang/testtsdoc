


# DeviceErrorTypeZeroFps constant







int const DeviceErrorTypeZeroFps
  




<p>Description: The frame rate of the capture device is 0.<br>Cause: Device error, or device does not have permission.<br>Solutions: Please use the system's video or audio recording application to check whether the device can work normally. Please check whether the application has correctly applied for the camera or microphone permission, and whether the user has granted the corresponding permission. If the device is normal and the application has obtained the corresponding device permissions, please contact ZEGO technical support.</p>



## Implementation

```dart
static const int DeviceErrorTypeZeroFps = 1006004;
```







