


# prefixWidget method








TextSpan prefixWidget
()








## Implementation

```dart
TextSpan prefixWidget() {
  const messageHostColor = Color(0xff9f76ff);

  return TextSpan(children: [
    WidgetSpan(
      child: Transform.translate(
        offset: Offset(0, 0.r),
        child: ConstrainedBox(
          constraints: BoxConstraints(
            maxWidth: 34.r + prefix!.length * 12.r,
            minWidth: 34.r,
            minHeight: 36.r,
            maxHeight: 36.r,
          ),
          child: Container(
            decoration: BoxDecoration(
              color: messageHostColor,
              borderRadius: BorderRadius.all(Radius.circular(20.r)),
            ),
            child: Padding(
              padding: EdgeInsets.fromLTRB(12.r, 4.r, 12.r, 4.r),
              child: Center(
                child: Text(
                  prefix!,
                  style: TextStyle(
                    color: Colors.white,
                    fontSize: 20.r,
                  ),
                ),
              ),
            ),
          ),
        ),
      ),
    ),
    WidgetSpan(child: SizedBox(width: 10.r)),
  ]);
}
```







