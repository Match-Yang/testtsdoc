


# Permission class









<p>Defines the permissions which can be checked and requested.</p>






**Implementers**

- [PermissionWithService](../zego_uikit_prebuilt_live_audio_room/PermissionWithService-class.md)

**Available Extensions**

- [PermissionActions](../zego_uikit_prebuilt_live_audio_room/PermissionActions.md)
- [PermissionCheckShortcuts](../zego_uikit_prebuilt_live_audio_room/PermissionCheckShortcuts.md)


**Annotations**

- @immutable


## Constructors

[Permission.byValue](../zego_uikit_prebuilt_live_audio_room/Permission/Permission.byValue.md) (int value)

Creates a <a href="../zego_uikit_prebuilt_live_audio_room/Permission-class.md">Permission</a> using the supplied integer value.   _factory_


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/Permission/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">override</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/Permission/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [value](../zego_uikit_prebuilt_live_audio_room/Permission/value.md) &#8594; int



Integer representation of the <a href="../zego_uikit_prebuilt_live_audio_room/Permission-class.md">Permission</a>.  
_<span class="feature">final</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/Permission/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/Permission/toString.md)() String



A string representation of this object.  
_<span class="feature">override</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/Permission/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">override</span>_










## Constants

##### [accessMediaLocation](../zego_uikit_prebuilt_live_audio_room/Permission/accessMediaLocation-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Allows an application to access any geographic locations
persisted in the user's shared collection.  




##### [accessNotificationPolicy](../zego_uikit_prebuilt_live_audio_room/Permission/accessNotificationPolicy-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Allows the user to access the notification policy of the phone.
EX: Allows app to turn on and off do-not-disturb.
iOS: Nothing  




##### [activityRecognition](../zego_uikit_prebuilt_live_audio_room/Permission/activityRecognition-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



When running on Android Q and above: Activity Recognition
When running on Android &lt; Q: Nothing
iOS: Nothing  




##### [appTrackingTransparency](../zego_uikit_prebuilt_live_audio_room/Permission/appTrackingTransparency-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Nothing
iOS: Allows user to accept that your app collects data about end users and
shares it with other companies for purposes of tracking across apps and
websites.  




##### [audio](../zego_uikit_prebuilt_live_audio_room/Permission/audio-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



When running on Android T and above: Read audio files from external storage
When running on Android &lt; T: Nothing
iOS: Nothing  




##### [bluetooth](../zego_uikit_prebuilt_live_audio_room/Permission/bluetooth-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



iOS 13 and above: The authorization state of Core Bluetooth manager.
When running &lt; iOS 13 or Android this is always allowed.  




##### [bluetoothAdvertise](../zego_uikit_prebuilt_live_audio_room/Permission/bluetoothAdvertise-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Allows the user to make this device discoverable to other
Bluetooth devices.
iOS: Nothing  




##### [bluetoothConnect](../zego_uikit_prebuilt_live_audio_room/Permission/bluetoothConnect-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Allows the user to connect with already paired Bluetooth devices.
iOS: Nothing  




##### [bluetoothScan](../zego_uikit_prebuilt_live_audio_room/Permission/bluetoothScan-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Allows the user to look for Bluetooth devices
(e.g. BLE peripherals).
iOS: Nothing  




##### [calendar](../zego_uikit_prebuilt_live_audio_room/Permission/calendar-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Calendar
iOS: Calendar (Events)  




##### [camera](../zego_uikit_prebuilt_live_audio_room/Permission/camera-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Camera
iOS: Photos (Camera Roll and Camera)  




##### [contacts](../zego_uikit_prebuilt_live_audio_room/Permission/contacts-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Contacts
iOS: AddressBook  




##### [criticalAlerts](../zego_uikit_prebuilt_live_audio_room/Permission/criticalAlerts-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Nothing
iOS: Notifications that override your ringer  




##### [ignoreBatteryOptimizations](../zego_uikit_prebuilt_live_audio_room/Permission/ignoreBatteryOptimizations-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Ignore Battery Optimizations  




##### [location](../zego_uikit_prebuilt_live_audio_room/Permission/location-constant.md) const [PermissionWithService](../zego_uikit_prebuilt_live_audio_room/PermissionWithService-class.md)



Android: Fine and Coarse Location
iOS: CoreLocation (Always and WhenInUse)  




##### [locationAlways](../zego_uikit_prebuilt_live_audio_room/Permission/locationAlways-constant.md) const [PermissionWithService](../zego_uikit_prebuilt_live_audio_room/PermissionWithService-class.md)



Android:
When running on Android &lt; Q: Fine and Coarse Location
When running on Android Q and above: Background Location Permission
iOS: CoreLocation - Always
When requesting this permission the user needs to grant permission
for the <code>locationWhenInUse</code> permission first, clicking on
  the <code>Àllow While Using App</code> option on the popup.
  After allowing the permission the user can request the <code>locationAlways</code>
  permission and can click on the <code>Change To Always Allow</code> option.  




##### [locationWhenInUse](../zego_uikit_prebuilt_live_audio_room/Permission/locationWhenInUse-constant.md) const [PermissionWithService](../zego_uikit_prebuilt_live_audio_room/PermissionWithService-class.md)



Android: Fine and Coarse Location
iOS: CoreLocation - WhenInUse  




##### [manageExternalStorage](../zego_uikit_prebuilt_live_audio_room/Permission/manageExternalStorage-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Allows an application a broad access to external storage in
scoped storage.
iOS: Nothing  




##### [mediaLibrary](../zego_uikit_prebuilt_live_audio_room/Permission/mediaLibrary-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: None
iOS: MPMediaLibrary  




##### [microphone](../zego_uikit_prebuilt_live_audio_room/Permission/microphone-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Microphone
iOS: Microphone  




##### [nearbyWifiDevices](../zego_uikit_prebuilt_live_audio_room/Permission/nearbyWifiDevices-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Allows the user to connect to nearby devices via Wi-Fi
iOS: Nothing  




##### [notification](../zego_uikit_prebuilt_live_audio_room/Permission/notification-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Notification
iOS: Notification  




##### [phone](../zego_uikit_prebuilt_live_audio_room/Permission/phone-constant.md) const [PermissionWithService](../zego_uikit_prebuilt_live_audio_room/PermissionWithService-class.md)



Android: Phone
iOS: Nothing  




##### [photos](../zego_uikit_prebuilt_live_audio_room/Permission/photos-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



When running on Android T and above: Read image files from external storage
When running on Android &lt; T: Nothing
iOS: Photos
iOS 14+ read &amp; write access level  




##### [photosAddOnly](../zego_uikit_prebuilt_live_audio_room/Permission/photosAddOnly-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Nothing
iOS: Photos
iOS 14+ read &amp; write access level  




##### [reminders](../zego_uikit_prebuilt_live_audio_room/Permission/reminders-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Nothing
iOS: Reminders  




##### [requestInstallPackages](../zego_uikit_prebuilt_live_audio_room/Permission/requestInstallPackages-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Allows an app to request installing packages.
iOS: Nothing  




##### [scheduleExactAlarm](../zego_uikit_prebuilt_live_audio_room/Permission/scheduleExactAlarm-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



When running on Android S and above: Allows exact alarm functionality
When running on Android &lt; S: Nothing
iOS: Nothing  




##### [sensors](../zego_uikit_prebuilt_live_audio_room/Permission/sensors-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Body Sensors
iOS: CoreMotion  




##### [sms](../zego_uikit_prebuilt_live_audio_room/Permission/sms-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Sms
iOS: Nothing  




##### [speech](../zego_uikit_prebuilt_live_audio_room/Permission/speech-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Microphone
iOS: Speech  




##### [storage](../zego_uikit_prebuilt_live_audio_room/Permission/storage-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: External Storage
iOS: Access to folders like <code>Documents</code> or <code>Downloads</code>. Implicitly
granted.  




##### [systemAlertWindow](../zego_uikit_prebuilt_live_audio_room/Permission/systemAlertWindow-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



Android: Allows an app to create windows shown on top of all other apps
iOS: Nothing  




##### [unknown](../zego_uikit_prebuilt_live_audio_room/Permission/unknown-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



The unknown only used for return type, never requested  




##### [values](../zego_uikit_prebuilt_live_audio_room/Permission/values-constant.md) const List&lt;[Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)>



Returns a list of all possible <code>PermissionGroup</code> values.  




##### [videos](../zego_uikit_prebuilt_live_audio_room/Permission/videos-constant.md) const [Permission](../zego_uikit_prebuilt_live_audio_room/Permission-class.md)



When running on Android T and above: Read video files from external storage
When running on Android &lt; T: Nothing
iOS: Nothing  









