


# ZegoPlayStreamQuality class









<p>Played stream quality information.</p>
<p>Audio and video parameters and network quality, etc.</p>




## Constructors

[ZegoPlayStreamQuality](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/ZegoPlayStreamQuality.md) (double videoRecvFPS, double videoDejitterFPS, double videoDecodeFPS, double videoRenderFPS, double videoKBPS, double videoBreakRate, double audioRecvFPS, double audioDejitterFPS, double audioDecodeFPS, double audioRenderFPS, double audioKBPS, double audioBreakRate, double mos, int rtt, double packetLostRate, int peerToPeerDelay, double peerToPeerPacketLostRate, [ZegoStreamQualityLevel](../zego_uikit_prebuilt_live_audio_room/ZegoStreamQualityLevel.md) level, int delay, int avTimestampDiff, bool isHardwareDecode, [ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md) videoCodecID, double totalRecvBytes, double audioRecvBytes, double videoRecvBytes)

   


## Properties

##### [audioBreakRate](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/audioBreakRate.md) &#8596; double



Audio break rate, the unit is (number of breaks / every 10 seconds) (Available since 1.17.0)  
_<span class="feature">read / write</span>_



##### [audioDecodeFPS](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/audioDecodeFPS.md) &#8596; double



Audio decoding frame rate. The unit of frame rate is f/s  
_<span class="feature">read / write</span>_



##### [audioDejitterFPS](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/audioDejitterFPS.md) &#8596; double



Audio dejitter frame rate. The unit of frame rate is f/s (Available since 1.17.0)  
_<span class="feature">read / write</span>_



##### [audioKBPS](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/audioKBPS.md) &#8596; double



Audio bit rate in kbps  
_<span class="feature">read / write</span>_



##### [audioRecvBytes](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/audioRecvBytes.md) &#8596; double



Number of audio bytes received  
_<span class="feature">read / write</span>_



##### [audioRecvFPS](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/audioRecvFPS.md) &#8596; double



Audio receiving frame rate. The unit of frame rate is f/s  
_<span class="feature">read / write</span>_



##### [audioRenderFPS](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/audioRenderFPS.md) &#8596; double



Audio rendering frame rate. The unit of frame rate is f/s  
_<span class="feature">read / write</span>_



##### [avTimestampDiff](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/avTimestampDiff.md) &#8596; int



The difference between the video timestamp and the audio timestamp, used to reflect the synchronization of audio and video, in milliseconds. This value is less than 0 means the number of milliseconds that the video leads the audio, greater than 0 means the number of milliseconds that the video lags the audio, and 0 means no difference. When the absolute value is less than 200, it can basically be regarded as synchronized audio and video, when the absolute value is greater than 200 for 10 consecutive seconds, it can be regarded as abnormal (Available since 1.19.0)  
_<span class="feature">read / write</span>_



##### [delay](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/delay.md) &#8596; int



Delay after the data is received by the local end, in milliseconds  
_<span class="feature">read / write</span>_



##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [isHardwareDecode](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/isHardwareDecode.md) &#8596; bool



Whether to enable hardware decoding  
_<span class="feature">read / write</span>_



##### [level](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/level.md) &#8596; [ZegoStreamQualityLevel](../zego_uikit_prebuilt_live_audio_room/ZegoStreamQualityLevel.md)



Published stream quality level  
_<span class="feature">read / write</span>_



##### [mos](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/mos.md) &#8596; double



The audio quality of the playing stream determined by the audio MOS (Mean Opinion Score) measurement method, value range <code>-1, 5</code>, where -1 means unknown, <code>0, 5</code> means valid score, the higher the score, the better the audio quality. For the subjective perception corresponding to the MOS value, please refer to <a href="https://docs.zegocloud.com/article/3720#4_4">https://docs.zegocloud.com/article/3720#4_4</a> (Available since 2.16.0)  
_<span class="feature">read / write</span>_



##### [packetLostRate](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/packetLostRate.md) &#8596; double



Packet loss rate, in percentage, 0.0 ~ 1.0  
_<span class="feature">read / write</span>_



##### [peerToPeerDelay](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/peerToPeerDelay.md) &#8596; int



Delay from peer to peer, in milliseconds  
_<span class="feature">read / write</span>_



##### [peerToPeerPacketLostRate](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/peerToPeerPacketLostRate.md) &#8596; double



Packet loss rate from peer to peer, in percentage, 0.0 ~ 1.0  
_<span class="feature">read / write</span>_



##### [rtt](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/rtt.md) &#8596; int



Server to local delay, in milliseconds  
_<span class="feature">read / write</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [totalRecvBytes](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/totalRecvBytes.md) &#8596; double



Total number of bytes received, including audio, video, SEI  
_<span class="feature">read / write</span>_



##### [videoBreakRate](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/videoBreakRate.md) &#8596; double



Video break rate, the unit is (number of breaks / every 10 seconds) (Available since 1.17.0)  
_<span class="feature">read / write</span>_



##### [videoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/videoCodecID.md) &#8596; [ZegoVideoCodecID](../zego_uikit_prebuilt_live_audio_room/ZegoVideoCodecID.md)



Video codec ID (Available since 1.17.0)  
_<span class="feature">read / write</span>_



##### [videoDecodeFPS](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/videoDecodeFPS.md) &#8596; double



Video decoding frame rate. The unit of frame rate is f/s  
_<span class="feature">read / write</span>_



##### [videoDejitterFPS](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/videoDejitterFPS.md) &#8596; double



Video dejitter frame rate. The unit of frame rate is f/s (Available since 1.17.0)  
_<span class="feature">read / write</span>_



##### [videoKBPS](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/videoKBPS.md) &#8596; double



Video bit rate in kbps  
_<span class="feature">read / write</span>_



##### [videoRecvBytes](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/videoRecvBytes.md) &#8596; double



Number of video bytes received  
_<span class="feature">read / write</span>_



##### [videoRecvFPS](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/videoRecvFPS.md) &#8596; double



Video receiving frame rate. The unit of frame rate is f/s  
_<span class="feature">read / write</span>_



##### [videoRenderFPS](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/videoRenderFPS.md) &#8596; double



Video rendering frame rate. The unit of frame rate is f/s  
_<span class="feature">read / write</span>_





## Methods

##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoPlayStreamQuality/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















