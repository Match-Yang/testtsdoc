


# avatarBuilder property







[ZegoAvatarBuilder](../../zego_uikit_prebuilt_live_audio_room/ZegoAvatarBuilder.md)? avatarBuilder
  
_<span class="feature">read / write</span>_



<p>Use this to customize the avatar, and replace the default avatar with it.</p>
<p>以下是示例代码：</p>
<pre class="language-dart"><code class="language-dart">
 // eg:
 avatarBuilder: (BuildContext context, Size size, ZegoUIKitUser? user, Map extraInfo) {
   return user != null
       ? Container(
           decoration: BoxDecoration(
             shape: BoxShape.circle,
             image: DecorationImage(
               image: NetworkImage(
                 'https://your_server/app/avatar/${user.id}.png',
               ),
             ),
           ),
         )
       : const SizedBox();
 },

</code></pre>



## Implementation

```dart
ZegoAvatarBuilder? avatarBuilder;
```







