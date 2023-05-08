


# ZIMRoomMemberQueriedResult class









<p>Callback of the result of querying the room members list.</p>
<p>Available since: 1.1.0 or above.</p>
<p>Description: Callback for the result of querying the room member list.</p>
<p>Related APIs: Query the list of room members through <code>queryRoomMember</code>, and the query result will be notified through this callback.</p>
<p><a href="../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult/memberList.md">memberList</a> List of members in the room.
<a href="../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult/nextFlag.md">nextFlag</a> The flag of the paging query. If this field is an empty string, the query has been completed. Otherwise, you need to set this value to the "nextFlag" field of ZIMRoomMemberQueryConfig for the next page query.</p>




## Constructors

[ZIMRoomMemberQueriedResult](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult/ZIMRoomMemberQueriedResult.md) ({required String roomID, required String nextFlag, required List&lt;[ZIMUserInfo](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo-class.md)> memberList})

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [memberList](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult/memberList.md) &#8596; List&lt;[ZIMUserInfo](../zego_uikit_prebuilt_live_audio_room/ZIMUserInfo-class.md)>



  
_<span class="feature">read / write</span>_



##### [nextFlag](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult/nextFlag.md) &#8596; String



  
_<span class="feature">read / write</span>_



##### [roomID](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult/roomID.md) &#8596; String



  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZIMRoomMemberQueriedResult/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















