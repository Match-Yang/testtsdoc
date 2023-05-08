


# ZIMUsersInfoQueriedResult class









<p>Supported version: 2.0.0 and above.</p>
<p>Detailed description: Callback after developer queries user information.</p>
<p>Use cases: The developer can check whether the login succeeded by using <code>errorCode</code> in this callback.</p>
<p>Notification timing: This callback is triggered when a developer invokes the <code>queryUserInfo</code> interface.</p>
<p>Related interface: Run the queryUserInfo command to query information.</p>
<p><a href="../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult/userList.md">userList</a>  List of the userInfo queried.
<a href="../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult/errorUserList.md">errorUserList</a> Failed to query the userInfo list.</p>




## Constructors

[ZIMUsersInfoQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult/ZIMUsersInfoQueriedResult.md) ({required List&lt;[ZIMUserFullInfo](../zego_uikit_prebuilt_live_audio_room/ZIMUserFullInfo-class.md)> userList, required List&lt;[ZIMErrorUserInfo](../zego_uikit_prebuilt_live_audio_room/ZIMErrorUserInfo-class.md)> errorUserList})

   


## Properties

##### [errorUserList](../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult/errorUserList.md) &#8596; List&lt;[ZIMErrorUserInfo](../zego_uikit_prebuilt_live_audio_room/ZIMErrorUserInfo-class.md)>



  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [userList](../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult/userList.md) &#8596; List&lt;[ZIMUserFullInfo](../zego_uikit_prebuilt_live_audio_room/ZIMUserFullInfo-class.md)>



  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZIMUsersInfoQueriedResult/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















