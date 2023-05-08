


# ZegoUser class









<p>User object.</p>
<p>Configure user ID and username to identify users in the room.
Note that the userID must be unique under the same appID, otherwise, there will be mutual kicks when logging in to the room.
It is strongly recommended that userID corresponds to the user ID of the business APP, that is, a userID and a real user are fixed and unique, and should not be passed to the SDK in a random userID. Because the unique and fixed userID allows ZEGO technicians to quickly locate online problems.</p>




## Constructors

[ZegoUser](../zego_uikit_prebuilt_live_audio_room/ZegoUser/ZegoUser.md) (String userID, String userName)

   

[ZegoUser.id](../zego_uikit_prebuilt_live_audio_room/ZegoUser/ZegoUser.id.md) (String userID)

Create a ZegoUser object   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoUser/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoUser/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [userID](../zego_uikit_prebuilt_live_audio_room/ZegoUser/userID.md) &#8596; String



User ID, a utf8 string with a maximum length of 64 bytes or less.Privacy reminder: Please do not fill in sensitive user information in this field, including but not limited to mobile phone number, ID number, passport number, real name, etc.Caution: Only support numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', '’', ',', '.', '&lt;', '&gt;', '/', ''.Do not use '%' if you need to communicate with the Web SDK.  
_<span class="feature">read / write</span>_



##### [userName](../zego_uikit_prebuilt_live_audio_room/ZegoUser/userName.md) &#8596; String



User Name, a utf8 string with a maximum length of 256 bytes or less.Please do not fill in sensitive user information in this field, including but not limited to mobile phone number, ID number, passport number, real name, etc.  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoUser/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoUser/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoUser/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















