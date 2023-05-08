


# debugCanApplyOutOfTurn method







- @protected

bool debugCanApplyOutOfTurn
()

_<span class="feature">inherited</span>_



<p>Whether the <code>ParentDataElement.applyWidgetOutOfTurn</code> method is allowed
with this widget.</p>
<p>This should only return true if this widget represents a <code>ParentData</code>
configuration that will have no impact on the layout or paint phase.</p>
<p>See also:</p>
<ul>
<li><code>ParentDataElement.applyWidgetOutOfTurn</code>, which verifies this in debug
mode.</li>
</ul>



## Implementation

```dart
@protected
bool debugCanApplyOutOfTurn() => false;
```







