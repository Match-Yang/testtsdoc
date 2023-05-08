


# ZegoAudioEffectPlayer class













## Constructors

[ZegoAudioEffectPlayer](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/ZegoAudioEffectPlayer.md) ()

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [getCurrentProgress](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/getCurrentProgress.md)(int audioEffectID) Future&lt;int>



Get current playback progress.  




##### [getIndex](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/getIndex.md)() int



Get audio effect player index.  




##### [getTotalDuration](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/getTotalDuration.md)(int audioEffectID) Future&lt;int>



Get the total duration of the specified audio effect resource.  




##### [loadResource](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/loadResource.md)(int audioEffectID, String path) Future&lt;[ZegoAudioEffectPlayerLoadResourceResult](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayerLoadResourceResult-class.md)>



Load audio effect resource.  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [pause](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/pause.md)(int audioEffectID) Future&lt;void>



Pause playing audio effect.  




##### [pauseAll](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/pauseAll.md)() Future&lt;void>



Pause playing all audio effect.  




##### [resume](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/resume.md)(int audioEffectID) Future&lt;void>



Resume playing audio effect.  




##### [resumeAll](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/resumeAll.md)() Future&lt;void>



Resume playing all audio effect.  




##### [seekTo](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/seekTo.md)(int audioEffectID, int millisecond) Future&lt;[ZegoAudioEffectPlayerSeekToResult](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayerSeekToResult-class.md)>



Set the specified playback progress.  




##### [setPlaySpeed](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/setPlaySpeed.md)(int audioEffectID, double speed) Future&lt;void>



Set the playback speed for a given audio effect. Both the local play speed and the publish speed are set. (separate settings are not supported).  




##### [setVolume](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/setVolume.md)(int audioEffectID, int volume) Future&lt;void>



Set volume for a single audio effect. Both the local play volume and the publish volume are set.  




##### [setVolumeAll](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/setVolumeAll.md)(int volume) Future&lt;void>



Set volume for all audio effect. Both the local play volume and the publish volume are set.  




##### [start](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/start.md)(int audioEffectID, {String? path, [ZegoAudioEffectPlayConfig](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayConfig-class.md)? config}) Future&lt;void>



Start playing audio effect.  




##### [stop](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/stop.md)(int audioEffectID) Future&lt;void>



Stop playing audio effect.  




##### [stopAll](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/stopAll.md)() Future&lt;void>



Stop playing all audio effect.  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_



##### [unloadResource](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/unloadResource.md)(int audioEffectID) Future&lt;void>



Unload audio effect resource.  






## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoAudioEffectPlayer/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















