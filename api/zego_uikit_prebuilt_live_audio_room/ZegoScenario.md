


# ZegoScenario enum







<p>Room scenario.</p>



**Inheritance**

- Object
- Enum
- ZegoScenario






## Constructors

[ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario/ZegoScenario.md) ()

  _const_ 


## Values

##### [~~General~~](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) const [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)



<p><code>Deprecated</code> Legacy general scenario, this scenario has been deprecated since version 3.0.0, and it is not recommended to use, please migrate to other new scenario as soon as possible.</p>  




##### [~~Communication~~](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) const [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)



<p><code>Deprecated</code> Legacy communication scenario, this scenario has been deprecated since version 3.0.0, and it is not recommended to use, please migrate to other new scenario as soon as possible.</p>  




##### [~~Live~~](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) const [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)



<p><code>Deprecated</code> Legacy live broadcast scenario, this scenario has been deprecated since version 3.0.0, and it is not recommended to use, please migrate to other new scenario as soon as possible.</p>  




##### [Default](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) const [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)



<p>Available since: 3.0.0. Description: The default (generic) scenario. If none of the following scenarios conform to your actual application scenario, this default scenario can be used.</p>  




##### [StandardVideoCall](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) const [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)



<p>Available since: 3.0.0. Description: Standard video call (or voice call) scenario, it is suitable for one-to-one video or voice call scenarios.</p>  




##### [HighQualityVideoCall](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) const [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)



<p>Available since: 3.0.0. Description: High quality video call (or voice call) scenario, it is similar to the standard video call scenario, but this scenario uses a higher video frame rate, bit rate, and resolution (540p) by default, which is suitable for video call scenario with high image quality requirements.</p>  




##### [StandardChatroom](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) const [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)



<p>Available since: 3.0.0. Description: Standard chatroom scenario, suitable for multi-person pure voice calls (low data usage). Note: On the ExpressVideo SDK, the camera is not enabled by default in this scenario.</p>  




##### [HighQualityChatroom](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) const [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)



<p>Available since: 3.0.0. Description: High quality chatroom scenario, it is similar to the standard chatroom scenario, but this scenario uses a higher audio bit rate than the standard chatroom scenario by default. It is suitable for multi-person pure voice call scenarios with high requirements on sound quality. Note: On the ExpressVideo SDK, the camera is not enabled by default in this scenario. The web platform does not currently support this scenario.</p>  




##### [Broadcast](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) const [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)



<p>Available since: 3.0.0. Description: Live broadcast scenario, it is suitable for one-to-many live broadcast scenarios such as shows, games, e-commerce, and large educational classes. The audio and video quality, fluency, and compatibility have been optimized. Note: Even in live broadcast scenarios, the SDK has no business "roles" (such as anchors and viewers), and all users in the room can publish and play streams.</p>  




##### [Karaoke](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) const [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)



<p>Available since: 3.0.0. Description: Karaoke (KTV) scenario, it is suitable for real-time chorus and online karaoke scenarios, and has optimized delay, sound quality, ear return, echo cancellation, etc., and also ensures accurate alignment and ultra-low delay when multiple people chorus. The web platform does not currently support this scenario.</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoScenario/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZegoScenario/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoScenario/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoScenario/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoScenario/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoScenario/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZegoScenario/values-constant.md) const List&lt;[ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)>



A constant List of the values in this enum, in order of their declaration.  









