


# ZegoPlayerConfig class









<p>Advanced player configuration.</p>
<p>Configure stream resource mode, CDN configuration and other advanced configurations.</p>




## Constructors

[ZegoPlayerConfig](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/ZegoPlayerConfig.md) ([ZegoStreamResourceMode](../zego_uikit_prebuilt_live_audio_room/ZegoStreamResourceMode.md) resourceMode, {[ZegoCDNConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig-class.md)? cdnConfig, String? roomID, [ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md)? videoCodecID, [ZegoResourceType](../zego_uikit_prebuilt_live_audio_room/ZegoResourceType.md)? sourceResourceType, int? codecTemplateID})

   

[ZegoPlayerConfig.defaultConfig](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/ZegoPlayerConfig.defaultConfig.md) ()

Create a default advanced player config object   


## Properties

##### [cdnConfig](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/cdnConfig.md) &#8596; [ZegoCDNConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig-class.md)?



The CDN configuration for playing stream. If set, the stream is play according to the URL instead of the streamID. After that, the streamID is only used as the ID of SDK internal callback.  
_<span class="feature">read / write</span>_



##### [codecTemplateID](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/codecTemplateID.md) &#8596; int?



Preconfigured codec template ID, please contact ZEGO technical support if you need to use it, otherwise this parameter can be ignored.  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [resourceMode](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/resourceMode.md) &#8596; [ZegoStreamResourceMode](../zego_uikit_prebuilt_live_audio_room/ZegoStreamResourceMode.md)



Stream resource mode.  
_<span class="feature">read / write</span>_



##### [roomID](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/roomID.md) &#8596; String?



The Room ID. It only needs to be filled in the multi-room mode, which indicates which room this stream needs to be bound to. This parameter is ignored in single room mode.  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [sourceResourceType](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/sourceResourceType.md) &#8596; [ZegoResourceType](../zego_uikit_prebuilt_live_audio_room/ZegoResourceType.md)?



The resource type of the source stream, please contact ZEGO technical support if you need to use it, otherwise this parameter can be ignored.  
_<span class="feature">read / write</span>_



##### [videoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/videoCodecID.md) &#8596; [ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md)?



The video encoding type of the stream, please contact ZEGO technical support if you need to use it, otherwise this parameter can be ignored.  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoPlayerConfig/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















