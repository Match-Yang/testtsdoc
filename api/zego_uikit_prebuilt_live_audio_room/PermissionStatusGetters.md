


# PermissionStatusGetters extension
on [PermissionStatus](../zego_uikit_prebuilt_live_audio_room/PermissionStatus.md)










<p>Utility getter extensions for the <a href="../zego_uikit_prebuilt_live_audio_room/PermissionStatus.md">PermissionStatus</a> type.</p>




## Properties

##### [isDenied](../zego_uikit_prebuilt_live_audio_room/PermissionStatusGetters/isDenied.md) &#8594; bool



If the user denied access to the requested feature,
permission needs to be asked first.  
_<span class="feature">read-only</span>_



##### [isGranted](../zego_uikit_prebuilt_live_audio_room/PermissionStatusGetters/isGranted.md) &#8594; bool



If the user granted access to the requested feature.  
_<span class="feature">read-only</span>_



##### [isLimited](../zego_uikit_prebuilt_live_audio_room/PermissionStatusGetters/isLimited.md) &#8594; bool



Indicates that permission for limited use of the resource is granted.  
_<span class="feature">read-only</span>_



##### [isPermanentlyDenied](../zego_uikit_prebuilt_live_audio_room/PermissionStatusGetters/isPermanentlyDenied.md) &#8594; bool



<em>On Android:</em>
If the user denied access to the requested feature and selected to never
again show a request for this permission (pre API 30) or the user denied
permissions for a second time (API 30 and higher).
The user may still change the permission status in the settings.  
_<span class="feature">read-only</span>_



##### [isRestricted](../zego_uikit_prebuilt_live_audio_room/PermissionStatusGetters/isRestricted.md) &#8594; bool



If the OS denied access to the requested feature. The user cannot change
this app's status, possibly due to active restrictions such as parental
controls being in place.
<em>Only supported on iOS.</em>  
_<span class="feature">read-only</span>_



















