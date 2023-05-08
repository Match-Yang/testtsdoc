


# ZegoRemoteDeviceState enum







<p>Remote device status.</p>



**Inheritance**

- Object
- Enum
- ZegoRemoteDeviceState






## Constructors

[ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState/ZegoRemoteDeviceState.md) ()

  _const_ 


## Values

##### [Open](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>Device on</p>  




##### [GenericError](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>General device error</p>  




##### [InvalidID](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>Invalid device ID</p>  




##### [NoAuthorization](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>No permission</p>  




##### [ZeroFPS](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>Captured frame rate is 0</p>  




##### [InUseByOther](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>The device is occupied</p>  




##### [Unplugged](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>The device is not plugged in or unplugged</p>  




##### [RebootRequired](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>The system needs to be restarted</p>  




##### [SystemMediaServicesLost](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>System media services stop, such as under the iOS platform, when the system detects that the current pressure is huge (such as playing a lot of animation), it is possible to disable all media related services.</p>  




##### [Disable](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>The remote user calls <code>enableCamera</code> or <code>muteMicrophone</code> to disable the camera or microphone.</p>  




##### [Mute](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>The remote user actively calls <code>mutePublishStreamAudio</code> or <code>mutePublishStreamVideo</code> to stop publish the audio or video stream.</p>  




##### [Interruption](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>The device is interrupted, such as a phone call interruption, etc.</p>  




##### [InBackground](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>There are multiple apps at the same time in the foreground, such as the iPad app split screen, the system will prohibit all apps from using the camera.</p>  




##### [MultiForegroundApp](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>CDN server actively disconnected</p>  




##### [BySystemPressure](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>The system is under high load pressure and may cause abnormal equipment.</p>  




##### [NotSupport](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md) const [ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)



<p>The remote device is not supported to publish the device state.</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState/values-constant.md) const List&lt;[ZegoRemoteDeviceState](../zego_uikit_prebuilt_live_audio_room/ZegoRemoteDeviceState.md)>



A constant List of the values in this enum, in order of their declaration.  









