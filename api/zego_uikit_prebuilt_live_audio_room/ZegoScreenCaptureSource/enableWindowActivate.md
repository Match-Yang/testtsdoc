


# enableWindowActivate method








Future&lt;void> enableWindowActivate
(bool active)





<p>Whether to activate the promotion of the window to the foreground.</p>
<p>Available since: 3.1.0
Description: When the capture target is a window, set whether to activate the window to be displayed in the foreground during the first capture.
When to call: It can be called after the engine by <code>createScreenCaptureSource</code> has been initialized.
Restrictions: Only support in Windows/macOS.</p>
<ul>
<li><code>active</code> Whether to activate the window. true to activate the window, false to not activate the window, the default is true.</li>
</ul>



## Implementation

```dart
Future<void> enableWindowActivate(bool active);
```







