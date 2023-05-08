


# GridLayoutDelegate.autoFill constructor







GridLayoutDelegate.autoFill({required List&lt;LayoutId> autoFillItems, required int columnCount, Size layoutPadding = const Size(2.0, 2.0), Size itemPadding = const Size(2.0, 2.0), [GridLayoutAlignment](../../zego_uikit_prebuilt_live_audio_room/GridLayoutAlignment.md) lastRowAlignment = GridLayoutAlignment.start})


<p>all items will auto fill up, layout will the SAME height as the screen
so make sure you have wrap CustomMultiChildLayout with Container with height</p>
<p>|I|
or
|I I|
|I I|
or
|I I I|
|I I I|
|I I  |</p>
<p>example:</p>
<p>final items = List.generate(5, (index) {
return LayoutId(
id: index,
child: Container(color: Colors.red<code>100 * (index % 8 + 1)</code>),
   );
 });</p>
<p>return SingleChildScrollView(
child: SizedBox(
//  you must wrap CustomMultiChildLayout with Container with height
height: MediaQuery.of(context).size.height,
child: CustomMultiChildLayout(
delegate: GridLayoutDelegate.autoFill(
normalItems: items,
columnCount: 3,
lastRowAlignment: GridLayoutAlignment.center,
),
children: items,
),
),
);</p>



## Implementation

```dart
GridLayoutDelegate.autoFill({
  required this.autoFillItems,
  required this.columnCount,
  this.layoutPadding = const Size(2.0, 2.0),
  this.itemPadding = const Size(2.0, 2.0),
  this.lastRowAlignment = GridLayoutAlignment.start,
}) : assert(columnCount > 0) {
  if (autoFillItems.length < columnCount) {
    columnCount = autoFillItems.length;
  }
}
```







