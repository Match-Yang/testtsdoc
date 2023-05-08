


# ZegoEngineProfile class









<p>Profile for create engine</p>
<p>Profile for create engine</p>




## Constructors

[ZegoEngineProfile](../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile/ZegoEngineProfile.md) (int appID, [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) scenario, {String? appSign, bool? enablePlatformView})

   


## Properties

##### [appID](../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile/appID.md) &#8596; int



Application ID issued by ZEGO for developers, please apply from the ZEGO Admin Console <a href="https://console.zegocloud.com">https://console.zegocloud.com</a> The value ranges from 0 to 4294967295.  
_<span class="feature">read / write</span>_



##### [appSign](../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile/appSign.md) &#8596; String?



Application signature for each AppID, please apply from the ZEGO Admin Console. Application signature is a 64 character string. Each character has a range of '0' ~ '9', 'a' ~ 'z'. AppSign 2.17.0 and later allows null or no transmission. If the token is passed empty or not passed, the token must be entered in the <a href="../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig-class.md">ZegoRoomConfig</a> parameter for authentication when the <code>loginRoom</code> interface is called to login to the room.  
_<span class="feature">read / write</span>_



##### [enablePlatformView](../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile/enablePlatformView.md) &#8596; bool?



Set whether to use Platform View for rendering, true: rendering using Platform View, false: rendering using Texture, default is false. Currently the web platform only supports rendering with Platform View. When using the <code>createCanvasView</code> interface, If the preferred render mode is not supported, another render mode is automatically used.  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [scenario](../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile/scenario.md) &#8596; [ZegoScenario](../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md)



The room scenario. the SDK will optimize the audio and video configuration for the specified scenario to achieve the best effect in this scenario. After specifying the scenario, you can call other APIs to adjusting the audio and video configuration. Differences between scenarios and how to choose a suitable scenario, please refer to <a href="https://docs.zegocloud.com/article/14940">https://docs.zegocloud.com/article/14940</a>  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















