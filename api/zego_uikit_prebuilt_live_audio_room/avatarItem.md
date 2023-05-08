


# avatarItem function










Widget avatarItem
(BuildContext context, [ZegoUIKitUser](../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md) user, [ZegoAvatarBuilder](../zego_uikit_prebuilt_live_audio_room/ZegoAvatarBuilder.md)? builder)








## Implementation

```dart
Widget avatarItem(
  BuildContext context,
  ZegoUIKitUser user,
  ZegoAvatarBuilder? builder,
) {
  return Container(
    width: 72.r,
    height: 72.r,
    decoration:
        const BoxDecoration(color: Color(0xffDBDDE3), shape: BoxShape.circle),
    child: Center(
      child: ValueListenableBuilder(
        valueListenable: ZegoUIKitUserPropertiesNotifier(user),
        builder: (context, _, __) {
          return builder?.call(context, Size(72.r, 72.r), user, {}) ??
              Text(
                user.name.isNotEmpty ? user.name.characters.first : '',
                style: TextStyle(
                  fontSize: 32.0.r,
                  color: const Color(0xff222222),
                  decoration: TextDecoration.none,
                ),
              );
        },
      ),
    ),
  );
}
```







