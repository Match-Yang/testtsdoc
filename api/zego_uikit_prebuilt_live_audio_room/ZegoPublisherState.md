


# ZegoPublisherState enum







<p>Publish stream status.</p>



**Inheritance**

- Object
- Enum
- ZegoPublisherState






## Constructors

[ZegoPublisherState](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState/ZegoPublisherState.md) ()

  _const_ 


## Values

##### [NoPublish](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState.md) const [ZegoPublisherState](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState.md)



<p>The state is not published, and it is in this state before publishing the stream. If a steady-state exception occurs in the publish process, such as AppID or Token are incorrect, or if other users are already publishing the stream, there will be a failure and enter this state.</p>  




##### [PublishRequesting](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState.md) const [ZegoPublisherState](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState.md)



<p>The state that it is requesting to publish the stream after the <code>startPublishingStream</code> function is successfully called. The UI is usually displayed through this state. If the connection is interrupted due to poor network quality, the SDK will perform an internal retry and will return to the requesting state.</p>  




##### [Publishing](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState.md) const [ZegoPublisherState](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState.md)



<p>The state that the stream is being published, entering the state indicates that the stream has been successfully published, and the user can communicate normally.</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState/values-constant.md) const List&lt;[ZegoPublisherState](../zego_uikit_prebuilt_live_audio_room/ZegoPublisherState.md)>



A constant List of the values in this enum, in order of their declaration.  









