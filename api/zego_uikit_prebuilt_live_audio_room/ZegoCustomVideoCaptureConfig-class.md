


# ZegoCustomVideoCaptureConfig class









<p>Custom video capture configuration.</p>
<p>Custom video capture, that is, the developer is responsible for collecting video data and sending the collected video data to SDK for video data encoding and publishing to the ZEGO RTC server. This feature is generally used by developers who use third-party beauty features or record game screen living.
When you need to use the custom video capture function, you need to set an instance of this class as a parameter to the <code>enableCustomVideoCapture</code> function.
Because when using custom video capture, SDK will no longer start the camera to capture video data. You need to collect video data from video sources by yourself.</p>




## Constructors

[ZegoCustomVideoCaptureConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCustomVideoCaptureConfig/ZegoCustomVideoCaptureConfig.md) ([ZegoVideoBufferType](../zego_uikit_prebuilt_live_audio_room/ZegoVideoBufferType.md) bufferType)

   


## Properties

##### [bufferType](../zego_uikit_prebuilt_live_audio_room/ZegoCustomVideoCaptureConfig/bufferType.md) &#8596; [ZegoVideoBufferType](../zego_uikit_prebuilt_live_audio_room/ZegoVideoBufferType.md)



Custom video capture video frame data type  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoCustomVideoCaptureConfig/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoCustomVideoCaptureConfig/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoCustomVideoCaptureConfig/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoCustomVideoCaptureConfig/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoCustomVideoCaptureConfig/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















