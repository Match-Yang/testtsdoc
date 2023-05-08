


# ZegoSignalingPluginCallKitEventImpl class













**Implemented types**

- [ZegoSignalingPluginCallKitEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent-mixin.md)


**Implementers**

- [ZegoUIKitSignalingPlugin](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitSignalingPlugin-class.md)





## Constructors

[ZegoSignalingPluginCallKitEventImpl](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/ZegoSignalingPluginCallKitEventImpl.md) ()

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEvent/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [getCallkitActivateAudioEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitActivateAudioEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider's audio session activation state changes.  
_<span class="feature">override</span>_



##### [getCallkitDeactivateAudioEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitDeactivateAudioEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



  
_<span class="feature">override</span>_



##### [getCallkitPerformAnswerCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformAnswerCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">override</span>_



##### [getCallkitPerformEndCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformEndCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">override</span>_



##### [getCallkitPerformPlayDTMFCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformPlayDTMFCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">override</span>_



##### [getCallkitPerformSetGroupCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformSetGroupCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">override</span>_



##### [getCallkitPerformSetHeldCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformSetHeldCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



  
_<span class="feature">override</span>_



##### [getCallkitPerformSetMutedCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformSetMutedCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitSetMutedCallActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitSetMutedCallActionEvent-class.md)>



  
_<span class="feature">override</span>_



##### [getCallkitPerformStartCallActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitPerformStartCallActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



each perform*CallAction method is called sequentially for each action in the transaction  
_<span class="feature">override</span>_



##### [getCallkitProviderDidBeginEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitProviderDidBeginEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider has been fully created and is ready to send actions and receive updates  
_<span class="feature">override</span>_



##### [getCallkitProviderDidResetEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitProviderDidResetEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitVoidEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitVoidEvent-class.md)>



Called when the provider has been reset. Delegates must respond to this callback by cleaning up all internal call state (disconnecting communication channels, releasing network resources, etc.). This callback can be treated as a request to end all calls without the need to respond to any actions  
_<span class="feature">override</span>_



##### [getCallkitTimedOutPerformingActionEventStream](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitEventImpl/getCallkitTimedOutPerformingActionEventStream.md)() Stream&lt;[ZegoSignalingPluginCallKitActionEvent](../zego_uikit_prebuilt_live_audio_room/ZegoSignalingPluginCallKitActionEvent-class.md)>



Called when an action was not performed in time and has been inherently failed. Depending on the action, this timeout may also force the call to end. An action that has already timed out should not be fulfilled or failed by the provider delegate  
_<span class="feature">override</span>_



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















