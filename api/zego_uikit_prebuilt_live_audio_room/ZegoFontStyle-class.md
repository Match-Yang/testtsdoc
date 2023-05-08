


# ZegoFontStyle class









<p>Font style.</p>
<p>Description: Font style configuration, can be used to configure font type, font size, font color, font transparency.
Use cases: Set text watermark in manual stream mixing scene, such as Co-hosting.</p>




## Constructors

[ZegoFontStyle](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/ZegoFontStyle.md) ([ZegoFontType](../zego_uikit_prebuilt_live_audio_room/ZegoFontType.md) type, int size, int color, int transparency, bool border, int borderColor)

   

[ZegoFontStyle.defaultStyle](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/ZegoFontStyle.defaultStyle.md) ()

Create a default font style object.   


## Properties

##### [border](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/border.md) &#8596; bool



Whether the font has a border. Required: False. Default value: False. Value range: True/False.  
_<span class="feature">read / write</span>_



##### [borderColor](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/borderColor.md) &#8596; int



Font border color, the calculation formula is: R + G x 256 + B x 65536, the value range of R (red), G (green), and B (blue) <code>0,255</code>. Required: False. Default value: 0. Value range: <code>0,16777215</code>.  
_<span class="feature">read / write</span>_



##### [color](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/color.md) &#8596; int



Font color, the calculation formula is: R + G x 256 + B x 65536, the value range of R (red), G (green), and B (blue) <code>0,255</code>. Required: False. Default value: 16777215(white). Value range: <code>0,16777215</code>.  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [size](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/size.md) &#8596; int



Font size in px. Required: False. Default value: 24. Value range: <code>12,100</code>.  
_<span class="feature">read / write</span>_



##### [transparency](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/transparency.md) &#8596; int



Font transparency. Required: False. Default value: 0. Value range: <code>0,100</code>, 100 is completely opaque, 0 is completely transparent.  
_<span class="feature">read / write</span>_



##### [type](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/type.md) &#8596; [ZegoFontType](../zego_uikit_prebuilt_live_audio_room/ZegoFontType.md)



Font type. Required: False. Default value: Source han sans <code>ZegoFontTypeSourceHanSans</code>  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toMap](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/toMap.md)() Map&lt;String, dynamic>



  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoFontStyle/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















