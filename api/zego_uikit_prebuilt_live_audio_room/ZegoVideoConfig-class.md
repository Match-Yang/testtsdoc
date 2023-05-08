


# ZegoVideoConfig class









<p>Video config.</p>
<p>Configure parameters used for publishing stream, such as bitrate, frame rate, and resolution.
Developers should note that the width and height resolution of the mobile and desktop are opposite. For example, 360p, the resolution of the mobile is 360x640, and the desktop is 640x360.
When using external capture, the capture and encoding resolution of RTC cannot be set to 0*0, otherwise, there will be no video data in the publishing stream in the entire engine life cycle.</p>




## Constructors

[ZegoVideoConfig](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/ZegoVideoConfig.md) (int captureWidth, int captureHeight, int encodeWidth, int encodeHeight, int fps, int bitrate, [ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) codecID, {int? keyFrameInterval})

   

[ZegoVideoConfig.preset](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/ZegoVideoConfig.preset.md) ([ZegoVideoConfigPreset](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfigPreset.md) preset)

Create video configuration with preset enumeration values   


## Properties

##### [bitrate](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/bitrate.md) &#8596; int



Bit rate in kbps. The settings before and after publishing stream can be effective  
_<span class="feature">read / write</span>_



##### [captureHeight](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/captureHeight.md) &#8596; int



Capture resolution height, control the height of camera image acquisition. SDK requires this member to be set to an even number. Only the camera is not started and the custom video capture is not used, the setting is effective. For performance reasons, the SDK scales the video frame to the encoding resolution after capturing from camera and before rendering to the preview view. Therefore, the resolution of the preview image is the encoding resolution. If you need the resolution of the preview image to be this value, Please call <code>setCapturePipelineScaleMode</code> first to change the capture pipeline scale mode to <code>Post</code>  
_<span class="feature">read / write</span>_



##### [captureWidth](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/captureWidth.md) &#8596; int



Capture resolution width, control the width of camera image acquisition. SDK requires this member to be set to an even number. Only the camera is not started and the custom video capture is not used, the setting is effective. For performance reasons, the SDK scales the video frame to the encoding resolution after capturing from camera and before rendering to the preview view. Therefore, the resolution of the preview image is the encoding resolution. If you need the resolution of the preview image to be this value, Please call <code>setCapturePipelineScaleMode</code> first to change the capture pipeline scale mode to <code>Post</code>  
_<span class="feature">read / write</span>_



##### [codecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/codecID.md) &#8596; [ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md)



The codec id to be used, the default value is <code>default</code>. Settings only take effect before publishing stream  
_<span class="feature">read / write</span>_



##### [encodeHeight](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/encodeHeight.md) &#8596; int



Encode resolution height, control the image height of the encoder when publishing stream. SDK requires this member to be set to an even number. The settings before and after publishing stream can be effective  
_<span class="feature">read / write</span>_



##### [encodeWidth](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/encodeWidth.md) &#8596; int



Encode resolution width, control the image width of the encoder when publishing stream. SDK requires this member to be set to an even number. The settings before and after publishing stream can be effective  
_<span class="feature">read / write</span>_



##### [fps](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/fps.md) &#8596; int



Frame rate, control the frame rate of the camera and the frame rate of the encoder. Only the camera is not started, the setting is effective. Publishing stream set to 60 fps, playing stream to take effect need contact technical support  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [keyFrameInterval](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/keyFrameInterval.md) &#8596; int?



Video keyframe interval, in seconds. Required: No. Default value: 2 seconds. Value range: <code>2, 5</code>. Caution: The setting is only valid before pushing.  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoVideoConfig/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















