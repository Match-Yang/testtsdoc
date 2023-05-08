


# PermissionCheckShortcuts extension
on [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)










<p>Shortcuts for checking the <code>status</code> of a <a href="../zego_uikit_prebuilt_live_audio_room/Permission-class.md">Permission</a>.</p>




## Properties

##### [isDenied](../zego_uikit_prebuilt_live_audio_room/PermissionCheckShortcuts/isDenied.md) &#8594; Future&lt;bool>



If the user denied this permission.  
_<span class="feature">read-only</span>_



##### [isGranted](../zego_uikit_prebuilt_live_audio_room/PermissionCheckShortcuts/isGranted.md) &#8594; Future&lt;bool>



If the user granted this permission.  
_<span class="feature">read-only</span>_



##### [isLimited](../zego_uikit_prebuilt_live_audio_room/PermissionCheckShortcuts/isLimited.md) &#8594; Future&lt;bool>



User has authorized this application for limited photo library access.
<em>Only supported on iOS.(iOS14+)</em>  
_<span class="feature">read-only</span>_



##### [isPermanentlyDenied](../zego_uikit_prebuilt_live_audio_room/PermissionCheckShortcuts/isPermanentlyDenied.md) &#8594; Future&lt;bool>



Returns <code>true</code> when permissions are denied permanently.  
_<span class="feature">read-only</span>_



##### [isRestricted](../zego_uikit_prebuilt_live_audio_room/PermissionCheckShortcuts/isRestricted.md) &#8594; Future&lt;bool>



If the OS denied this permission. The user cannot change the status,
possibly due to active restrictions such as parental controls being in
place.
<em>Only supported on iOS.</em>  
_<span class="feature">read-only</span>_



















