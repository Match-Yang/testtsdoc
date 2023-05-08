


# appSign property







String? appSign
  
_<span class="feature">read / write</span>_



<p>Application signature for each AppID, please apply from the ZEGO Admin Console. Application signature is a 64 character string. Each character has a range of '0' ~ '9', 'a' ~ 'z'. AppSign 2.17.0 and later allows null or no transmission. If the token is passed empty or not passed, the token must be entered in the <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoRoomConfig-class.md">ZegoRoomConfig</a> parameter for authentication when the <code>loginRoom</code> interface is called to login to the room.</p>



## Implementation

```dart
String? appSign;
```







