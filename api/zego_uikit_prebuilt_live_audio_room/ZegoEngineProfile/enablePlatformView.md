


# enablePlatformView property







bool? enablePlatformView
  
_<span class="feature">read / write</span>_



<p>Set whether to use Platform View for rendering, true: rendering using Platform View, false: rendering using Texture, default is false. Currently the web platform only supports rendering with Platform View. When using the <code>createCanvasView</code> interface, If the preferred render mode is not supported, another render mode is automatically used.</p>



## Implementation

```dart
bool? enablePlatformView;
```







