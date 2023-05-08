


# ZegoRangeAudio class













## Constructors

[ZegoRangeAudio](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/ZegoRangeAudio.md) ()

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [enableMicrophone](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/enableMicrophone.md)(bool enable) Future&lt;void>



Turn the microphone on or off.  




##### [enableSpatializer](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/enableSpatializer.md)(bool enable) Future&lt;void>



Turn the 3D spatial sound on or off.  




##### [enableSpeaker](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/enableSpeaker.md)(bool enable) Future&lt;void>



Turn the speaker on or off.  




##### [muteUser](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/muteUser.md)(String userID, bool mute) Future&lt;void>



Whether can receive the audio data of the specified user.  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [setAudioReceiveRange](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/setAudioReceiveRange.md)(double range) Future&lt;void>



Set the maximum range of received audio.  




##### [setPositionUpdateFrequency](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/setPositionUpdateFrequency.md)(int frequency) Future&lt;void>



Set the frequency of real-time update locations within the SDK.  




##### [setRangeAudioMode](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/setRangeAudioMode.md)([ZegoRangeAudioMode](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudioMode.md) mode) Future&lt;void>



Set range audio mode.  




##### [setRangeAudioVolume](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/setRangeAudioVolume.md)(int volume) Future&lt;void>



Set range voice volume.  




##### [setStreamVocalRange](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/setStreamVocalRange.md)(String streamID, double vocalRange) Future&lt;void>



Set the sound range for the stream.  




##### [setTeamID](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/setTeamID.md)(String teamID) Future&lt;void>



Set team ID.  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [updateAudioSource](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/updateAudioSource.md)(String userID, Float32List position) Future&lt;void>



Add or update audio source position information.  




##### [updateSelfPosition](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/updateSelfPosition.md)(Float32List position, Float32List axisForward, Float32List axisRight, Float32List axisUp) Future&lt;void>



Update self position and orentation.  




##### [updateStreamPosition](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/updateStreamPosition.md)(String streamID, Float32List position) Future&lt;void>



Update the location of the flow.  






## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoRangeAudio/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















