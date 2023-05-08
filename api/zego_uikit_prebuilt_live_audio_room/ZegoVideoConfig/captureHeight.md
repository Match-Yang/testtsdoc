


# captureHeight property







int captureHeight
  
_<span class="feature">read / write</span>_



<p>Capture resolution height, control the height of camera image acquisition. SDK requires this member to be set to an even number. Only the camera is not started and the custom video capture is not used, the setting is effective. For performance reasons, the SDK scales the video frame to the encoding resolution after capturing from camera and before rendering to the preview view. Therefore, the resolution of the preview image is the encoding resolution. If you need the resolution of the preview image to be this value, Please call <code>setCapturePipelineScaleMode</code> first to change the capture pipeline scale mode to <code>Post</code></p>



## Implementation

```dart
int captureHeight;
```







