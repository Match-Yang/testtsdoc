


# serviceStatus property









Future&lt;[ServiceStatus](../../zego_uikit_prebuilt_live_audio_room/ServiceStatus.md)> serviceStatus
  




<p>Checks the current status of the service associated with this permission.</p>
<p>Notes about specific permissions:</p>
<ul>
<li><strong><a href="../../zego_uikit_prebuilt_live_audio_room/Permission/phone-constant.md">Permission.phone</a></strong>
<ul>
<li>Android:
<ul>
<li>The method will return <a href="../../zego_uikit_prebuilt_live_audio_room/ServiceStatus.md">ServiceStatus.notApplicable</a> when:
<ul>
<li>the device lacks the TELEPHONY feature</li>
<li>TelephonyManager.getPhoneType() returns PHONE_TYPE_NONE</li>
<li>when no Intents can be resolved to handle the <code>tel:</code> scheme</li>
</ul>
</li>
<li>The method will return <a href="../../zego_uikit_prebuilt_live_audio_room/ServiceStatus.md">ServiceStatus.disabled</a> when:
<ul>
<li>the SIM card is missing</li>
</ul>
</li>
</ul>
</li>
<li>iOS:
<ul>
<li>The method will return <a href="../../zego_uikit_prebuilt_live_audio_room/ServiceStatus.md">ServiceStatus.notApplicable</a> when:
<ul>
<li>the native code can not find a handler for the <code>tel:</code> scheme</li>
</ul>
</li>
<li>The method will return <a href="../../zego_uikit_prebuilt_live_audio_room/ServiceStatus.md">ServiceStatus.disabled</a> when:
<ul>
<li>the mobile network code (MNC) is either 0 or 65535. See
<a href="https://stackoverflow.com/a/11595365">https://stackoverflow.com/a/11595365</a> for details</li>
</ul>
</li>
</ul>
</li>
<li><strong>PLEASE NOTE that this is still not a perfect indication</strong> of the
device's capability to place &amp; connect phone calls as it also depends
on the network condition.</li>
</ul>
</li>
</ul>



## Implementation

```dart
Future<ServiceStatus> get serviceStatus => _handler.checkServiceStatus(this);
```








