


# ZegoCDNConfig class









<p>CDN config object.</p>
<p>Includes CDN URL and authentication parameter string</p>




## Constructors

[ZegoCDNConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/ZegoCDNConfig.md) (String url, {String? authParam, String? protocol, String? quicVersion, [ZegoHttpDNSType](../zego_uikit_prebuilt_live_audio_room/ZegoHttpDNSType.md)? httpdns})

   


## Properties

##### [authParam](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/authParam.md) &#8596; String?



Auth param of URL. Please contact ZEGO technical support if you need to use it, otherwise this parameter can be ignored (set to null or empty string).  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [httpdns](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/httpdns.md) &#8596; [ZegoHttpDNSType](../zego_uikit_prebuilt_live_audio_room/ZegoHttpDNSType.md)?



customized httpdns service. This feature is only supported for playing stream currently.  
_<span class="feature">read / write</span>_



##### [protocol](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/protocol.md) &#8596; String?



URL supported protocols, candidate values are "tcp" and "quic". If there are more than one, separate them with English commas and try them in order. Please contact ZEGO technical support if you need to use it, otherwise this parameter can be ignored (set to null or empty string).  
_<span class="feature">read / write</span>_



##### [quicVersion](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/quicVersion.md) &#8596; String?



QUIC version。 If <a href="../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/protocol.md">protocol</a> has the QUIC protocol, this information needs to be filled in. If there are multiple version numbers, separate them with commas. Please contact ZEGO technical support if you need to use it, otherwise this parameter can be ignored (set to null or empty string).  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [url](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/url.md) &#8596; String



CDN URL  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoCDNConfig/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















