


# showAlertDialog function










Future&lt;bool> showAlertDialog
(BuildContext context, String title, String content, List&lt;Widget> actions, {TextStyle? titleStyle, TextStyle? contentStyle, MainAxisAlignment? actionsAlignment, Color? backgroundColor})








## Implementation

```dart
Future<bool> showAlertDialog(
  BuildContext context,
  String title,
  String content,
  List<Widget> actions, {
  TextStyle? titleStyle,
  TextStyle? contentStyle,
  MainAxisAlignment? actionsAlignment,
  Color? backgroundColor,
}) async {
  return await showDialog(
        context: context,
        barrierDismissible: false,
        builder: (BuildContext context) {
          return CupertinoTheme(
            data: const CupertinoThemeData(brightness: Brightness.dark),
            child: CupertinoAlertDialog(
              title: Text(
                title,
                textAlign: TextAlign.center,
                style: titleStyle ??
                    TextStyle(
                      fontSize: 30.0.r,
                      fontWeight: FontWeight.bold,
                      color: const Color(0xff2A2A2A),
                    ),
              ),
              content: Text(
                content,
                textAlign: TextAlign.center,
                style: contentStyle ??
                    TextStyle(
                      fontSize: 28.0.r,
                      color: const Color(0xff2A2A2A),
                    ),
              ),
              actions: actions,
            ),
          );
        },
      ) ??
      false;
}
```







