


# ZIMMessageSentResult class









<p>Callback of the result of sending the message.</p>
<p>Available since: 1.1.0 or above.</p>
<p>Description: This callback is triggered when the developer calls the <code>sendPeerMessage</code> and <code>sendRoomMessage</code> interfaces. The developer can check whether the callback is sent successfully by <code>errorCode</code> in the callback.</p>
<p><a href="../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult/message.md">message</a> The sent message object, from which parameters such as messageID can be obtained. If the sending fails, the messageID parameter in the message will be an empty string.</p>




## Constructors

[ZIMMessageSentResult](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult/ZIMMessageSentResult.md) ({required [ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md) message})

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [message](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult/message.md) &#8596; [ZIMMessage](../zego_uikit_prebuilt_live_audio_room/ZIMMessage-class.md)



  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZIMMessageSentResult/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















