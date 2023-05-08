


# downloadMediaFile method








Future&lt;[ZIMMediaDownloadedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMMediaDownloadedResult-class.md)> downloadMediaFile
([ZIMMediaMessage](../../zego_uikit_prebuilt_live_audio_room/ZIMMediaMessage-class.md) message, [ZIMMediaFileType](../../zego_uikit_prebuilt_live_audio_room/ZIMMediaFileType.md) fileType, [ZIMMediaDownloadingProgress](../../zego_uikit_prebuilt_live_audio_room/ZIMMediaDownloadingProgress.md)? progress)





<p>Download media message content.</p>
<p>Supported versions: 2.1.5 and above.</p>
<p>Detailed description: This method can be used to download the content of media messages, including the original image, large image, thumbnail image, file message, audio message, video message and the first frame of the image message.</p>
<p>Service scenario: After the user receives a message, if the message is a media message, he can call this API to download its content.</p>
<p>Invoke timing/notification timing: can be invoked after logging in and receiving a media message.</p>
<p><code>message</code> The message to be received.
<code>fileType</code> Media file type
<code>progress</code> Callback of the progress.</p>



## Implementation

```dart
Future<ZIMMediaDownloadedResult> downloadMediaFile(ZIMMediaMessage message,
    ZIMMediaFileType fileType, ZIMMediaDownloadingProgress? progress);
```







