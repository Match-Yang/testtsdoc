


# enableCursorVisible method








Future&lt;void> enableCursorVisible
(bool visible)





<p>Set whether to show the cursor</p>
<p>Available since: 3.1.0
Description: Set whether to show the cursor.
When to call: It can be called after the engine by <code>createScreenCaptureSource</code> has been initialized.
Restrictions: Only support in Windows/macOS.</p>
<ul>
<li><code>visible</code> Whether to show the cursor. true to show the cursor, false to not show the cursor, the default is false.</li>
</ul>



## Implementation

```dart
Future<void> enableCursorVisible(bool visible);
```







