

# ZegoUIKitPrebuiltLiveAudioRoom class

<p>语聊房 Widget。你可以将该 Widget嵌入到你项目的任何页面以集成语聊房的功能。</p>

## Constructors

`ZegoUIKitPrebuiltLiveAudioRoom` ({Key? key, required int appID, required String appSign, required String userID, required String userName, required String roomID, required `ZegoUIKitPrebuiltLiveAudioRoomConfig` config, `ZegoLiveAudioRoomController`? controller, @Deprecated(&#39;Since 2.4.1&#39;) Size? appDesignSize})

  _const_ 

## Properties

##### `appDesignSize` &#8594; Size?

_<span class="feature">final</span>_

##### `appID` &#8594; int

你可以在 <a href="https://console.zegocloud.com">https://console.zegocloud.com</a> 创建项目并获取到appID  
_<span class="feature">final</span>_

##### `appSign` &#8594; String

你可以在 <a href="https://console.zegocloud.com">https://console.zegocloud.com</a> 创建项目并获取到appSign  
_<span class="feature">final</span>_

##### `config` &#8594; `ZegoUIKitPrebuiltLiveAudioRoomConfig`

初始化语聊房的配置  
_<span class="feature">final</span>_

##### `controller` &#8594; `ZegoLiveAudioRoomController`?

可以通过<code>controller</code>调用 <code>ZegoUIKitPrebuiltLiveAudioRoom</code> 中提供的方法  
_<span class="feature">final</span>_



##### `roomID` &#8594; String

语聊房的id。
这个id是这个房间的唯一标识所以你需要确保唯一性。可以是任意有效字符串。
填写了同一个<code>roomID</code>的用户都会登录到同一个房间进行聊天或者听别人聊天。  
_<span class="feature">final</span>_


##### `userID` &#8594; String

当前登录用户的id。可以是任意有效字符串。一般使用你自己用户系统中的id即可，比如Firebase。  
_<span class="feature">final</span>_

##### `userName` &#8594; String

当前登录用户的名称。可以是任意有效字符串。一般使用你自己用户系统中的名称即可，比如Firebase。  
_<span class="feature">final</span>_
