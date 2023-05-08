


# ZegoCopyrightedMusicBillingMode enum







<p>VOD billing mode.</p>



**Inheritance**

- Object
- Enum
- ZegoCopyrightedMusicBillingMode






## Constructors

[ZegoCopyrightedMusicBillingMode](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode/ZegoCopyrightedMusicBillingMode.md) ()

  _const_ 


## Values

##### [Count](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode.md) const [ZegoCopyrightedMusicBillingMode](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode.md)



<p>Pay-per-use.Each time a user obtains a song resource, a charge is required, that is, the user will be charged for each time based on the actual call to obtain the song resource interface (such as <code>requestSong</code>, <code>requestAccompaniment</code>, etc.).</p>  




##### [User](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode.md) const [ZegoCopyrightedMusicBillingMode](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode.md)



<p>Monthly billing by user.Billing for a single user is based on the monthly dimension, that is, the statistics call to obtain song resources (such as <code>requestSong</code>, <code>requestAccompaniment</code>, etc.) and the parameters are the user ID of the monthly subscription, and the charging is based on the monthly dimension.</p>  




##### [Room](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode.md) const [ZegoCopyrightedMusicBillingMode](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode.md)



<p>Monthly billing by room.The room users are billed on a monthly basis, that is, statistical calls to obtain song resources (such as <code>requestSong</code>, <code>requestAccompaniment</code>, etc.) are passed as Roomid for a monthly subscription of the room, and fees are charged on a monthly basis.</p>  





## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [index](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode/index.md) &#8594; int



A numeric identifier for the enumerated value.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_










## Constants

##### [values](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode/values-constant.md) const List&lt;[ZegoCopyrightedMusicBillingMode](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicBillingMode.md)>



A constant List of the values in this enum, in order of their declaration.  









