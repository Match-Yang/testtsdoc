


# updateCaptureRegion method








Future&lt;void> updateCaptureRegion
(Rect rect)





<p>Update the area captured by the screen.</p>
<p>Available since: 3.1.0
Description: Update the area captured by the screen.
When to call: It can be called after the engine by <code>createScreenCaptureSource</code> has been initialized.
Restrictions: Only support in Windows/macOS.</p>
<ul>
<li><code>rect</code> The position of the area to be captured relative to the entire screen or window.</li>
</ul>



## Implementation

```dart
Future<void> updateCaptureRegion(Rect rect);
```







