


# circleName method








Widget circleName
(BuildContext context, Size size, [ZegoUIKitUser](../../zego_uikit_prebuilt_live_audio_room/ZegoUIKitUser-class.md)? user)








## Implementation

```dart
Widget circleName(BuildContext context, Size size, ZegoUIKitUser? user) {
  final userName = user?.name ?? '';
  return SizedBox.fromSize(
    size: size,
    child: Container(
      decoration: const BoxDecoration(
        color: Color(0xffDBDDE3),
        shape: BoxShape.circle,
      ),
      child: Center(
        child: Text(
          userName.isNotEmpty ? userName.characters.first : '',
          style: TextStyle(
            fontSize: showSoundLevel ? size.width / 4 : size.width / 5 * 4,
            color: const Color(0xff222222),
            decoration: TextDecoration.none,
          ),
        ),
      ),
    ),
  );
}
```







