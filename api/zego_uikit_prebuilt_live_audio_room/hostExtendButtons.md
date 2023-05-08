


# hostExtendButtons top-level property









List hostExtendButtons
  
_<span class="feature">read / write</span>_






## Implementation

```dart
...bottomMenuBarConfig.hostExtendButtons = [
  ZegoMenuExtendBarButton(
    index: 0,
    GestureDector(
      onTap: () {},
      child: Widget(),
    )
  )
]

/// 控制UI上文案
/// 通过修改对应属性的值达到修改UI上文案的能力。当然你也可以改成其他语言
/// 这个类被用于 ZegoUIKitPrebuiltLiveAudioRoomConfig.innerText 属性
/// 注意，文案中的 %0 占位符会被替换成对应的用户名
```








