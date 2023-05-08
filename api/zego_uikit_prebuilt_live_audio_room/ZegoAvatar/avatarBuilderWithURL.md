


# avatarBuilderWithURL method








Widget avatarBuilderWithURL
(BuildContext context, Size size, [ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)? user, Map&lt;String, dynamic> extraInfo)








## Implementation

```dart
Widget avatarBuilderWithURL(
  BuildContext context,
  Size size,
  ZegoUIKitUser? user,
  Map<String, dynamic> extraInfo,
) {
  return ValueListenableBuilder(
    valueListenable: ZegoUIKitUserPropertiesNotifier(
      user ?? ZegoUIKitUser.empty(),
    ),
    builder: (context, _, __) {
      final avatarURL = user?.inRoomAttributes.value.avatarURL ?? '';
      return avatarURL.isNotEmpty
          ? CachedNetworkImage(
              imageUrl: avatarURL,
              imageBuilder: (context, imageProvider) => Container(
                decoration: BoxDecoration(
                  shape: BoxShape.circle,
                  image: DecorationImage(
                    image: imageProvider,
                    fit: BoxFit.cover,
                  ),
                ),
              ),
              progressIndicatorBuilder: (context, url, downloadProgress) =>
                  CircularProgressIndicator(value: downloadProgress.progress),
              errorWidget: (context, url, error) {
                ZegoLoggerService.logInfo(
                  '${user?.toString()} avatar url is invalid',
                  tag: 'uikit',
                  subTag: 'avatar',
                );
                return circleName(context, avatarSize, user);
              },
            )
          : avatarBuilder?.call(
                context,
                size,
                user,
                extraInfo,
              ) ??
              circleName(context, avatarSize, user);
    },
  );
}
```







