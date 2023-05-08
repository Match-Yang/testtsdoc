


# ZegoSignalingPluginCallKitEvent mixin















**Mixin Applications**

- [ZegoSignalingPluginCallKitEventImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl-class.md)
- [ZegoSignalingPluginInterface](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginInterface-class.md)



## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [getCallkitActivateAudioEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitActivateAudioEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider's audio session activation state changes.  




##### [getCallkitDeactivateAudioEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitDeactivateAudioEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



  




##### [getCallkitPerformAnswerCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformAnswerCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  




##### [getCallkitPerformEndCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformEndCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  




##### [getCallkitPerformPlayDTMFCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformPlayDTMFCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  




##### [getCallkitPerformSetGroupCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformSetGroupCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  




##### [getCallkitPerformSetHeldCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformSetHeldCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  




##### [getCallkitPerformSetMutedCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformSetMutedCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitSetMutedCallActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitSetMutedCallActionEvent-class.md)>



  




##### [getCallkitPerformStartCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitPerformStartCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



each perform*CallAction method is called sequentially for each action in the transaction  




##### [getCallkitProviderDidBeginEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitProviderDidBeginEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider has been fully created and is ready to send actions and receive updates  




##### [getCallkitProviderDidResetEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitProviderDidResetEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider has been reset. Delegates must respond to this callback by cleaning up all internal call state (disconnecting communication channels, releasing network resources, etc.). This callback can be treated as a request to end all calls without the need to respond to any actions  




##### [getCallkitTimedOutPerformingActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/getCallkitTimedOutPerformingActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



Called when an action was not performed in time and has been inherently failed. Depending on the action, this timeout may also force the call to end. An action that has already timed out should not be fulfilled or failed by the provider delegate  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















