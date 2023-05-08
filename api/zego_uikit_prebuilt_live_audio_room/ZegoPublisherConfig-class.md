


# ZegoPublisherConfig class









<p>Advanced publisher configuration.</p>
<p>Configure room id</p>




## Constructors

[ZegoPublisherConfig](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherConfig/ZegoPublisherConfig.md) ({String? roomID, int? forceSynchronousNetworkTime, [ZegoStreamCensorshipMode](../zego_uikit_prebuilt_live_audio_room/ZegoStreamCensorshipMode.md)? streamCensorshipMode})

   


## Properties

##### [forceSynchronousNetworkTime](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherConfig/forceSynchronousNetworkTime.md) &#8596; int?



Whether to synchronize the network time when pushing streams. 1 is synchronized with 0 is not synchronized. And must be used with setStreamAlignmentProperty. It is used to align multiple streams at the mixed stream service or streaming end, such as the chorus scene of KTV.  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherConfig/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [roomID](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherConfig/roomID.md) &#8596; String?



The Room ID, It is not necessary to pass in single room mode, but the ID of the corresponding room must be passed in multi-room mode  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherConfig/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [streamCensorshipMode](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherConfig/streamCensorshipMode.md) &#8596; [ZegoStreamCensorshipMode](../zego_uikit_prebuilt_live_audio_room/ZegoStreamCensorshipMode.md)?



When pushing a flow, review the pattern of the flow. By default, no audit is performed. If you want to use this function, contact ZEGO technical support.  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherConfig/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherConfig/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherConfig/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















