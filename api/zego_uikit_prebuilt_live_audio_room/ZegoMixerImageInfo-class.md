


# ZegoMixerImageInfo class









<p>Set the image information of a single input stream in the mux.</p>
<p>Available since: 2.19.0
Description: Sets a picture for the content of a single input stream, which is used in place of the video, i.e. the video is not displayed when the picture is used. The <code>layout</code> layout in <a href="../zego_uikit_prebuilt_live_audio_room/ZegoMixerInput-class.md">ZegoMixerInput</a> for image multiplexing.
Use case: The developer needs to temporarily turn off the camera to display the image during the video connection to the microphone, or display the picture when the audio is connected to the microphone.
Restrictions: Image size is limited to 1M.</p>




## Constructors

[ZegoMixerImageInfo](../zego_uikit_prebuilt_live_audio_room/ZegoMixerImageInfo/ZegoMixerImageInfo.md) (String url)

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoMixerImageInfo/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoMixerImageInfo/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [url](../zego_uikit_prebuilt_live_audio_room/ZegoMixerImageInfo/url.md) &#8596; String



The image path, if not empty, the image will be displayed, otherwise, the video will be displayed. JPG and PNG formats are supported. There are 2 ways to use it: 1. URI: Provide the picture to ZEGO technical support for configuration. After the configuration is complete, the picture URI will be provided, for example: preset-id://xxx.jpg. 2. URL: Only HTTP protocol is supported.  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoMixerImageInfo/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toMap](../zego_uikit_prebuilt_live_audio_room/ZegoMixerImageInfo/toMap.md)() Map&lt;String, dynamic>



  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoMixerImageInfo/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoMixerImageInfo/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















