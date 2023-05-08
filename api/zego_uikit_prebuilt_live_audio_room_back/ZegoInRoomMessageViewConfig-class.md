

# ZegoInRoomMessageViewConfig class

<p>消息列表的控制项</p>

## Constructors

`ZegoInRoomMessageViewConfig` ({bool visible = true, ZegoInRoomMessageItemBuilder? itemBuilder})

## Properties


##### `itemBuilder` &#8596; ZegoInRoomMessageItemBuilder?

Use this to customize the every row of message view
比如你想更改当前消息列表的样式（比如背景颜色、透明度、圆角），或者增加额外信息（比如发消息这个人的等级、他的身份）等等，你就可以通过该builder方法实现。  
_<span class="feature">read / write</span>_


##### `visible` &#8596; bool

如果为<code>false</code>则消息列表会被隐藏起来。默认是<code>true</code>。  
_<span class="feature">read / write</span>_
