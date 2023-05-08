


# build method







- @override

Widget build
(BuildContext context)





<p>Describes the part of the user interface represented by this widget.</p>
<p>The framework calls this method when this widget is inserted into the tree
in a given <code>BuildContext</code> and when the dependencies of this widget change
(e.g., an <code>InheritedWidget</code> referenced by this widget changes). This
method can potentially be called in every frame and should not have any side
effects beyond building a widget.</p>
<p>The framework replaces the subtree below this widget with the widget
returned by this method, either by updating the existing subtree or by
removing the subtree and inflating a new subtree, depending on whether the
widget returned by this method can update the root of the existing
subtree, as determined by calling <code>Widget.canUpdate</code>.</p>
<p>Typically implementations return a newly created constellation of widgets
that are configured with information from this widget's constructor and
from the given <code>BuildContext</code>.</p>
<p>The given <code>BuildContext</code> contains information about the location in the
tree at which this widget is being built. For example, the context
provides the set of inherited widgets for this location in the tree. A
given widget might be built with multiple different <code>BuildContext</code>
arguments over time if the widget is moved around the tree or if the
widget is inserted into the tree in multiple places at once.</p>
<p>The implementation of this method must only depend on:</p>
<ul>
<li>the fields of the widget, which themselves must not change over time,
and</li>
<li>any ambient state obtained from the <code>context</code> using
<code>BuildContext.dependOnInheritedWidgetOfExactType</code>.</li>
</ul>
<p>If a widget's <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoLeaveButton/build.md">build</a> method is to depend on anything else, use a
<code>StatefulWidget</code> instead.</p>
<p>See also:</p>
<ul>
<li><code>StatelessWidget</code>, which contains the discussion on performance considerations.</li>
</ul>



## Implementation

```dart
@override
Widget build(BuildContext context) {
  final containerSize = buttonSize ?? Size(96.r, 96.r);
  final sizeBoxSize = iconSize ?? Size(56.r, 56.r);
  return GestureDetector(
    onTap: () async {
      ///  if there is a user-defined event before the click,
      ///  wait the synchronize execution result
      final isConfirm = await onLeaveConfirmation?.call(context) ?? true;
      if (isConfirm) {
        quit();
      }
    },
    child: Container(
      width: containerSize.width,
      height: containerSize.height,
      decoration: BoxDecoration(
        color: icon?.backgroundColor ?? Colors.red,
        borderRadius: BorderRadius.all(Radius.circular(
            math.min(containerSize.width, containerSize.height) / 2)),
      ),
      child: SizedBox.fromSize(
        size: sizeBoxSize,
        child:
            icon?.icon ?? UIKitImage.asset(StyleIconUrls.iconS1ControlBarEnd),
      ),
    ),
  );
}
```







