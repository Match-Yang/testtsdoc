


# ZegoMixerInput class









<p>Mixer input.</p>
<p>Configure the mix stream input stream ID, type, and the layout</p>




## Constructors

[ZegoMixerInput](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/ZegoMixerInput.md) (String streamID, [ZegoMixerInputContentType](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInputContentType.md) contentType, Rect layout, int soundLevelID, int volume, bool isAudioFocus, int audioDirection, {[ZegoLabelInfo](../zego_uikit_prebuilt_live_audio_room/ZegoLabelInfo-class.md)? label, [ZegoMixRenderMode](../zego_uikit_prebuilt_live_audio_room/ZegoMixRenderMode.md)? renderMode, [ZegoMixerImageInfo](../zego_uikit_prebuilt_live_audio_room/ZegoMixerImageInfo-class.md)? imageInfo, int? cornerRadius})

   

[ZegoMixerInput.defaultConfig](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/ZegoMixerInput.defaultConfig.md) ()

   


## Properties

##### [audioDirection](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/audioDirection.md) &#8596; int



The direction of the audio. Valid direction is between 0 to 360. Set -1 means disable. Default value is -1  
_<span class="feature">read / write</span>_



##### [contentType](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/contentType.md) &#8596; [ZegoMixerInputContentType](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInputContentType.md)



Mix stream content type  
_<span class="feature">read / write</span>_



##### [cornerRadius](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/cornerRadius.md) &#8596; int?



Description: Video frame corner radius, in px. Required: False. Value range: Does not exceed the width and height of the video screen set by the <a href="../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/layout.md">layout</a> parameter. Default value: 0.  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [imageInfo](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/imageInfo.md) &#8596; [ZegoMixerImageInfo](../zego_uikit_prebuilt_live_audio_room/ZegoMixerImageInfo-class.md)?



User image information.  
_<span class="feature">read / write</span>_



##### [isAudioFocus](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/isAudioFocus.md) &#8596; bool



Whether the focus voice is enabled in the current input stream, the sound of this stream will be highlighted if enabled  
_<span class="feature">read / write</span>_



##### [label](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/label.md) &#8596; [ZegoLabelInfo](../zego_uikit_prebuilt_live_audio_room/ZegoLabelInfo-class.md)?



Text watermark.  
_<span class="feature">read / write</span>_



##### [layout](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/layout.md) &#8596; Rect



Stream layout. When the mixed stream is an audio stream (that is, the ContentType parameter is set to the audio mixed stream type), the layout field is not processed inside the SDK, and there is no need to pay attention to this parameter.  
_<span class="feature">read / write</span>_



##### [renderMode](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/renderMode.md) &#8596; [ZegoMixRenderMode](../zego_uikit_prebuilt_live_audio_room/ZegoMixRenderMode.md)?



Video view render mode.  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [soundLevelID](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/soundLevelID.md) &#8596; int



If enable soundLevel in mix stream task, an unique soundLevelID is need for every stream  
_<span class="feature">read / write</span>_



##### [streamID](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/streamID.md) &#8596; String



Stream ID, a string of up to 256 characters. Caution: You cannot include URL keywords, otherwise publishing stream and playing stream will fails. Only support numbers, English characters and '-', '&nbsp;'.  
_<span class="feature">read / write</span>_



##### [volume](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/volume.md) &#8596; int



Input stream volume, valid range <code>0, 200</code>, default is 100  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toMap](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/toMap.md)() Map&lt;String, dynamic>



  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















