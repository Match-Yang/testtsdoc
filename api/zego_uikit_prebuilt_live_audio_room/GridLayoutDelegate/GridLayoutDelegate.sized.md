


# GridLayoutDelegate.sized constructor







GridLayoutDelegate.sized({required List&lt;[GridLayoutSizedItem](../../zego_uikit_prebuilt_live_audio_room/GridLayoutSizedItem-class.md)> sizedItems, required int columnCount, Size layoutPadding = const Size(2.0, 2.0), Size itemPadding = const Size(2.0, 2.0), [GridLayoutAlignment](../../zego_uikit_prebuilt_live_audio_room/GridLayoutAlignment.md) lastRowAlignment = GridLayoutAlignment.start})


<p>all items will auto layout according to the specified width and height, and will EXCEED the screen height</p>
<p>I I I
I I I
|I I I|
|I I I|
|I I I|
I I I
I I I</p>
<p>example:</p>
<p>var columnCount = 3;
var screenSize = MediaQuery.of(context).size;</p>
<p>final items = List.generate(20, (index) {
var width = screenSize.width / columnCount - 2.0;
var height = 120.0;
return GridLayoutSizedItem(
width: width,
height: height,
id: index,
child: Container(
width: width,
height: height,
color: Colors.red<code>100 * (index % 8 + 1)</code>,
     ),
   );
 });</p>
<p>return SingleChildScrollView(
child: CustomMultiChildLayout(
delegate: GridLayoutDelegate.sized(
sizedItems: items,
columnCount: columnCount,
lastRowAlignment: GridLayoutAlignment.center,
),
children: items,
),
);</p>



## Implementation

```dart
GridLayoutDelegate.sized({
  required this.sizedItems,
  required this.columnCount,
  this.layoutPadding = const Size(2.0, 2.0),
  this.itemPadding = const Size(2.0, 2.0),
  this.lastRowAlignment = GridLayoutAlignment.start,
}) : assert(columnCount > 0);
```







