


# createElement method







- @override

ParentDataElement&lt;MultiChildLayoutParentData> createElement
()

_<span class="feature">inherited</span>_



<p>Inflates this configuration to a concrete instance.</p>
<p>A given widget can be included in the tree zero or more times. In particular
a given widget can be placed in the tree multiple times. Each time a widget
is placed in the tree, it is inflated into an <code>Element</code>, which means a
widget that is incorporated into the tree multiple times will be inflated
multiple times.</p>



## Implementation

```dart
@override
ParentDataElement<T> createElement() => ParentDataElement<T>(this);
```







