


# ZIMMessageType enum







<p>The type of the message.</p>
<p>Description: Identifies the type of current message.</p>
<p>Use cases: It can be used to determine what type of message this message is.</p>



**Inheritance**

- Object
- Enum
- ZIMMessageType






## Constructors

[ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType/ZIMMessageType.md) ()

  _const_ 


## Values

##### [unknown](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md) const [ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md)



<p>Description: Unknown message.</p>
<p>Use cases: A message of an unknown type is received, indicating that the sender may have sent a message type that the user does not support, and the user needs to be advised to update the version.</p>  




##### [text](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md) const [ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md)



<p>Description: Normal text message.</p>
<p>Use cases: Can be used to deliver ordinary text messages.</p>  




##### [command](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md) const [ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md)



<p>Description: Custom binary message.</p>
<p>Use cases: Can be used to transfer custom binary messages. This message type does not support offline messages and local storage.</p>  




##### [barrage](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md) const [ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md)



<p>Description: Barrage message.</p>
<p>Use cases: Can be used for the barrage sent by the live room. This message type does not support offline messages and local storage.</p>  




##### [image](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md) const [ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md)



<p>Description: Image message.</p>
<p>Use cases: Can be used to send image messages, only ".jpg", ".jpeg", ".png", ".bmp", ".gif", ".tiff" image types are supported. After sending the image, the server will generate a large image and a thumbnail of the original image.</p>  




##### [file](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md) const [ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md)



<p>Description: File message.</p>
<p>Use cases: For sending file messages, no file type restrictions.</p>  




##### [audio](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md) const [ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md)



<p>Description: Audio message.</p>
<p>Use cases: For sending audio messages, only ".mp3" audio type is supported.</p>  




##### [video](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md) const [ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md)



<p>Description: Video message.</p>
<p>Use cases: For sending video messages, only ".mp4", ".mov" video types are supported. After sending the video message, the server will generate the first frame of the video file.</p>  




##### [system](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md) const [ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md)



  




##### [revoke](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md) const [ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md)



  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType/values-constant.md) const List&lt;[ZIMMessageType](../zego_uikit_prebuilt_live_audio_room/ZIMMessageType.md)>



A constant List of the values in this enum, in order of their declaration.  









