


# ZegoRoomConfig class









<p>Advanced room configuration.</p>
<p>Configure maximum number of users in the room and authentication token, etc.</p>




## Constructors

[ZegoRoomConfig](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig/ZegoRoomConfig.md) (int maxMemberCount, bool isUserStatusNotify, String token)

   

[ZegoRoomConfig.defaultConfig](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig/ZegoRoomConfig.defaultConfig.md) ()

Create a default room configuration   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [isUserStatusNotify](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig/isUserStatusNotify.md) &#8596; bool



Whether to enable the user in and out of the room callback notification <code>onRoomUserUpdate</code>, the default is off. If developers need to use ZEGO Room user notifications, make sure that each user who login sets this flag to true  
_<span class="feature">read / write</span>_



##### [maxMemberCount](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig/maxMemberCount.md) &#8596; int



The maximum number of users in the room, Passing 0 means unlimited, the default is unlimited.  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [token](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig/token.md) &#8596; String



The token issued by the developer's business server is used to ensure security. For the generation rules, please refer to <a href="https://doc-zh.zego.im/article/10360">Using Token Authentication</a>, the default is an empty string, that is, no authentication. In versions 2.17.0 and above, if appSign is not passed in when calling the <code>createEngine</code> API to create an engine, or if appSign is empty, this parameter must be set for authentication when logging in to a room.  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toMap](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig/toMap.md)() Map&lt;String, dynamic>



  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















