


# ZegoLogConfig class









<p>Log config.</p>
<p>Description: This parameter is required when calling <code>setlogconfig</code> to customize log configuration.
Use cases: This configuration is required when you need to customize the log storage path or the maximum log file size.
Caution: None.</p>




## Constructors

[ZegoLogConfig](../zego_uikit_prebuilt_live_audio_room/ZegoLogConfig/ZegoLogConfig.md) (String logPath, int logSize)

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoLogConfig/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [logPath](../zego_uikit_prebuilt_live_audio_room/ZegoLogConfig/logPath.md) &#8596; String



The storage path of the log file. Description: Used to customize the storage path of the log file. Use cases: This configuration is required when you need to customize the log storage path. Required: False. Default value: The default path of each platform is different, please refer to the official website document <a href="https://docs.zegocloud.com/faq/express_sdkLog">https://docs.zegocloud.com/faq/express_sdkLog</a>. Caution: Developers need to ensure read and write permissions for files under this path.  
_<span class="feature">read / write</span>_



##### [logSize](../zego_uikit_prebuilt_live_audio_room/ZegoLogConfig/logSize.md) &#8596; int



Maximum log file size(Bytes). Description: Used to customize the maximum log file size. Use cases: This configuration is required when you need to customize the upper limit of the log file size. Required: False. Default value: 5MB (5 * 1024 * 1024 Bytes). Value range: Minimum 1MB (1 * 1024 * 1024 Bytes), maximum 100M (100 * 1024 * 1024 Bytes), 0 means no need to write logs. Caution: The larger the upper limit of the log file size, the more log information it carries, but the log upload time will be longer.  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoLogConfig/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoLogConfig/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoLogConfig/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoLogConfig/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















