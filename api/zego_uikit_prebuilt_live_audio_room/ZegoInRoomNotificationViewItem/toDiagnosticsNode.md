


# toDiagnosticsNode method







- @override

DiagnosticsNode toDiagnosticsNode
({String? name, DiagnosticsTreeStyle? style})

_<span class="feature">inherited</span>_



<p>Returns a debug representation of the object that is used by debugging
tools and by <code>DiagnosticsNode.toStringDeep</code>.</p>
<p>Leave <code>name</code> as null if there is not a meaningful description of the
relationship between the this node and its parent.</p>
<p>Typically the <code>style</code> argument is only specified to indicate an atypical
relationship between the parent and the node. For example, pass
<code>DiagnosticsTreeStyle.offstage</code> to indicate that a node is offstage.</p>



## Implementation

```dart
@override
DiagnosticsNode toDiagnosticsNode({ String? name, DiagnosticsTreeStyle? style }) {
  return DiagnosticableTreeNode(
    name: name,
    value: this,
    style: style,
  );
}
```







