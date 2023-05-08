


# GridLayoutDelegate class









<p>two layout mode:</p>
<ol>
<li>auto fill mode:</li>
<li>sized mode:</li>
</ol>




## Constructors

[GridLayoutDelegate.autoFill](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/GridLayoutDelegate.autoFill.md) ({required List&lt;LayoutId> autoFillItems, required int columnCount, Size layoutPadding = const Size(2.0, 2.0), Size itemPadding = const Size(2.0, 2.0), [GridLayoutAlignment](../zego_uikit_prebuilt_live_audio_room/GridLayoutAlignment.md) lastRowAlignment = GridLayoutAlignment.start})

all items will auto fill up, layout will the SAME height as the screen
so make sure you have wrap CustomMultiChildLayout with Container with height   

[GridLayoutDelegate.sized](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/GridLayoutDelegate.sized.md) ({required List&lt;[GridLayoutSizedItem](../zego_uikit_prebuilt_live_audio_room/GridLayoutSizedItem-class.md)> sizedItems, required int columnCount, Size layoutPadding = const Size(2.0, 2.0), Size itemPadding = const Size(2.0, 2.0), [GridLayoutAlignment](../zego_uikit_prebuilt_live_audio_room/GridLayoutAlignment.md) lastRowAlignment = GridLayoutAlignment.start})

all items will auto layout according to the specified width and height, and will EXCEED the screen height   


## Properties

##### [autoFillItems](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/autoFillItems.md) &#8596; List&lt;LayoutId>



  
_<span class="feature">read / write</span>_



##### [columnCount](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/columnCount.md) &#8596; int



  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [itemPadding](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/itemPadding.md) &#8594; Size



  
_<span class="feature">final</span>_



##### [itemsPosition](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/itemsPosition.md) &#8596; List&lt;Offset>



  
_<span class="feature">read / write</span>_



##### [lastRowAlignment](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/lastRowAlignment.md) &#8594; [GridLayoutAlignment](../zego_uikit_prebuilt_live_audio_room/GridLayoutAlignment.md)



  
_<span class="feature">final</span>_



##### [layoutPadding](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/layoutPadding.md) &#8594; Size



  
_<span class="feature">final</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [sizedItems](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/sizedItems.md) &#8596; List&lt;[GridLayoutSizedItem](../zego_uikit_prebuilt_live_audio_room/GridLayoutSizedItem-class.md)>



  
_<span class="feature">read / write</span>_





## Methods

##### [convertSizedItemByAutoFill](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/convertSizedItemByAutoFill.md)(BoxConstraints constraints) void



  




##### [getSize](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/getSize.md)(BoxConstraints constraints) Size



Override this method to return the size of this object given the
incoming constraints.  




##### [hasChild](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/hasChild.md)(Object childId) bool



True if a non-null LayoutChild was provided for the specified id.  
_<span class="feature">inherited</span>_



##### [layoutChild](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/layoutChild.md)(Object childId, BoxConstraints constraints) Size



Ask the child to update its layout within the limits specified by
the constraints parameter. The child's size is returned.  
_<span class="feature">inherited</span>_



##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [performLayout](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/performLayout.md)(Size size) void



Override this method to lay out and position all children given this
widget's size.  




##### [positionChild](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/positionChild.md)(Object childId, Offset offset) void



Specify the child's origin relative to this origin.  
_<span class="feature">inherited</span>_



##### [shouldRelayout](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/shouldRelayout.md)(covariant MultiChildLayoutDelegate oldDelegate) bool



Override this method to return true when the children need to be
laid out.  




##### [toString](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/toString.md)() String



Override this method to include additional information in the
debugging data printed by <code>debugDumpRenderTree</code> and friends.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/GridLayoutDelegate/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















