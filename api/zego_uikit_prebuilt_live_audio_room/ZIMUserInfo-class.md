


# ZIMUserInfo class









<p>User information object.</p>
<p>Description: Identifies a unique user.</p>
<p>Caution: Note that the userID must be unique under the same appID, otherwise mutual kicks out will occur.
It is strongly recommended that userID corresponds to the user ID of the business APP,
that is, a userID and a real user are fixed and unique, and should not be passed to the SDK in a random userID.
Because the unique and fixed userID allows ZEGO technicians to quickly locate online problems.</p>






**Implementers**

- [ZIMGroupMemberInfo](../zego_uikit_prebuilt_live_audio_room/ZIMGroupMemberInfo-class.md)





## Constructors

[ZIMUserInfo](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo/ZIMUserInfo.md) ()

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [userID](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo/userID.md) &#8596; String



User ID, a string with a maximum length of 32 bytes or less. Only support numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', '’', ',', '.', '&lt;', '&gt;', '/', ''.  
_<span class="feature">read / write</span>_



##### [userName](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo/userName.md) &#8596; String



User name, a string with a maximum length of 64 bytes or less.  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















