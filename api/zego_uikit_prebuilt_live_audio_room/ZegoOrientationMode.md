


# ZegoOrientationMode enum







<p>Orientation mode of the video.</p>



**Inheritance**

- Object
- Enum
- ZegoOrientationMode






## Constructors

[ZegoOrientationMode](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode/ZegoOrientationMode.md) ()

  _const_ 


## Values

##### [Custom](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode.md) const [ZegoOrientationMode](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode.md)



<p>Custom mode.Description: The default is the custom mode. In this mode, the user needs to set the orientation through <code>SetAppOrientation</code>, and set the video resolution through <code>SetVideoConfig</code> to control the video ratio. The SDK rotates the video at the stream publishing end.</p>  




##### [Adaption](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode.md) const [ZegoOrientationMode](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode.md)



<p>Player self adaption mode.Description: The video orientation of the stream playing end is automatically vertically upward, and the user of the stream publishing end no longer needs to set the orientation through <code>SetAppOrientation</code>, and no longer need to set the video resolution to control the video ratio through <code>SetVideoConfig</code>. Caution: 1. Both the stream publishing end and the stream playing end need to be set to <code>ZegoOrientationModeAdaption</code> mode. 2. Media players, cloud recording, local recording, and publish or play streaming scenarios via CDN are not supported.  3. In this mode, the SDK will automatically swap the width and height of the encoding resolution according to the actual orientation of the device.</p>  




##### [Alignment](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode.md) const [ZegoOrientationMode](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode.md)



<p>Player adapt to pulisher mode.Description: Taking the Status Bar as a reference, the video direction of the stream playing end is the same as the preview video direction of the stream publishing end. The SDK will use the Status Bar as a reference to rotate the image on the stream playing end, and the rotation angle is the same as the rotation angle of the preview on the stream publishing end. Stream publishing end users no longer need to set the orientation through <code>SetAppOrientation</code>, and no longer need to set the video resolution to control the video ratio through <code>SetVideoConfig</code>. Caution: 1. Media players, cloud recording, local recording, and publish or play streaming scenarios via CDN are not supported.2. In this mode, the SDK will automatically swap the width and height of the encoding resolution according to the actual position of the Status Bar.</p>  




##### [FixedResolutionRatio](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode.md) const [ZegoOrientationMode](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode.md)



<p>Fixed resolution ratio mode.Description: Taking the Status Bar as a reference, the video orientation of the stream playing end is the same as the previewed video direction of the stream publishing end, and the video resolution is the same as the encoding resolution. Users of the streaming end no longer need to set the orientation through <code>SetAppOrientation</code>.</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode/values-constant.md) const List&lt;[ZegoOrientationMode](../zego_uikit_prebuilt_live_audio_room/ZegoOrientationMode.md)>



A constant List of the values in this enum, in order of their declaration.  









