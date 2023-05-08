


# toString method







- @override

String toString
()

_<span class="feature">override</span>_



<p>A string representation of this object.</p>
<p>Some classes have a default textual representation,
often paired with a static <code>parse</code> function (like <code>int.parse</code>).
These classes will provide the textual representation as
their string representation.</p>
<p>Other classes have no meaningful textual representation
that a program will care about.
Such classes will typically override <code>toString</code> to provide
useful information when inspecting the object,
mainly for debugging or logging.</p>



## Implementation

```dart
@override
String toString() => '{roomID: $roomID, '
    'state: $state, '
    'action: $action, '
    'extendedData: $extendedData}';
```







