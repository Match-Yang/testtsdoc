


# manageExternalStorage constant







[Permission](../../zego_uikit_prebuilt_live_audio_room/Permission-class.md) const manageExternalStorage
  




<p>Android: Allows an application a broad access to external storage in
scoped storage.
iOS: Nothing</p>
<p>You should request the Manage External Storage permission only when
your app cannot effectively make use of the more privacy-friendly APIs.
For more information: <a href="https://developer.android.com/training/data-storage/manage-all-files">https://developer.android.com/training/data-storage/manage-all-files</a></p>
<p>When the privacy-friendly APIs (i.e. <a href="https://developer.android.com/guide/topics/providers/document-provider">Storage Access Framework</a>
or the <a href="https://developer.android.com/training/data-storage/shared/media">MediaStore</a> APIs) is all your app needs the
<code>PermissionGroup.storage</code> are the only permissions you need to request.</p>
<p>If the usage of the Manage External Storage permission is needed,
you have to fill out the Permission Declaration Form upon submitting
your app to the Google Play Store. More details can be found here:
https://support.google.com/googleplay/android-developer/answer/9214102#zippy=</p>



## Implementation

```dart
static const manageExternalStorage = Permission._(22);
```







