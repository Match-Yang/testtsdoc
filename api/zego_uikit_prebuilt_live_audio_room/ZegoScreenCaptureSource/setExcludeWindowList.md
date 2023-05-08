


# setExcludeWindowList method








Future&lt;void> setExcludeWindowList
(List&lt;int> list)





<p>Sets the filtered list of windows.</p>
<p>Available since: 3.1.0
Description: Specify a list of windows, and filter these windows when capturing the screen, and not display them on the screen.
When to call: It can be called after the engine by <code>createScreenCaptureSource</code> has been initialized.
Restrictions: Only support in Windows/macOS.</p>
<ul>
<li><code>list</code> List of IDs to filter windows.</li>
</ul>



## Implementation

```dart
Future<void> setExcludeWindowList(List<int> list);
```







