


# showTopModalSheet&lt;T> function










Future&lt;T?> showTopModalSheet
&lt;T>(BuildContext context, Widget widget, {bool barrierDismissible = true})








## Implementation

```dart
Future<T?> showTopModalSheet<T>(BuildContext context, Widget widget,
    {bool barrierDismissible = true}) {
  return showGeneralDialog<T?>(
    context: context,
    barrierDismissible: barrierDismissible,
    transitionDuration: const Duration(milliseconds: 250),
    barrierLabel: MaterialLocalizations.of(context).dialogLabel,
    barrierColor: Colors.black.withOpacity(0.5),
    pageBuilder: (context, _, __) => ScreenUtilInit(
      designSize: const Size(750, 1334),
      minTextAdapt: true,
      splitScreenMode: true,
      builder: (context, child) {
        return SafeArea(
            child: Column(
          children: [
            SizedBox(height: 16.h),
            widget,
          ],
        ));
      },
    ),
    transitionBuilder: (context, animation, secondaryAnimation, child) {
      return SlideTransition(
        position: CurvedAnimation(parent: animation, curve: Curves.easeOutCubic)
            .drive(
                Tween<Offset>(begin: const Offset(0, -1.0), end: Offset.zero)),
        child: child,
      );
    },
  );
}
```







