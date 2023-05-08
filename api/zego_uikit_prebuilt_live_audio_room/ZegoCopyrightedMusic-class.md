


# ZegoCopyrightedMusic class













## Constructors

[ZegoCopyrightedMusic](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/ZegoCopyrightedMusic.md) ()

   


## Properties

##### [hashCode](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/hashCode.md) &#8594; int



The hash code for this object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_



##### [runtimeType](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/runtimeType.md) &#8594; Type



A representation of the runtime type of the object.  
_<span class="feature">read-only</span><span class="feature">inherited</span>_





## Methods

##### [clearCache](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/clearCache.md)() Future&lt;void>



Clear cache.  




##### [download](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/download.md)(String resourceID) Future&lt;[ZegoCopyrightedMusicDownloadResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicDownloadResult-class.md)>



Download song or accompaniment.  




##### [getAverageScore](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getAverageScore.md)(String resourceID) Future&lt;int>



Get average score.  




##### [getCacheSize](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getCacheSize.md)() Future&lt;int>



Get cache size.  




##### [getCurrentPitch](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getCurrentPitch.md)(String resourceID) Future&lt;int>



Get real-time pitch data.  




##### [getDuration](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getDuration.md)(String resourceID) Future&lt;int>



Get the playing time of a song or accompaniment file.  




##### [getFullScore](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getFullScore.md)(String resourceID) Future&lt;int>



Get full score .  




##### [getKrcLyricByToken](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getKrcLyricByToken.md)(String krcToken) Future&lt;[ZegoCopyrightedMusicGetKrcLyricByTokenResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetKrcLyricByTokenResult-class.md)>



Get lyrics in krc format.  




##### [getLrcLyric](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getLrcLyric.md)(String songID) Future&lt;[ZegoCopyrightedMusicGetLrcLyricResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetLrcLyricResult-class.md)>



Get lyrics in lrc format.  




##### [~~getMusicByToken~~](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getMusicByToken.md)(String shareToken) Future&lt;[ZegoCopyrightedMusicGetMusicByTokenResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetMusicByTokenResult-class.md)>



<code>Deprecated</code> Get a song or accompaniment. Deprecated since 3.0.2, please use the <a href="../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getSharedResource.md">getSharedResource</a> function instead.  




##### [getPreviousScore](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getPreviousScore.md)(String resourceID) Future&lt;int>



Get the score of the previous sentence.  




##### [getSharedResource](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getSharedResource.md)([ZegoCopyrightedMusicGetSharedConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetSharedConfig-class.md) config, [ZegoCopyrightedMusicResourceType](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicResourceType.md) type) Future&lt;[ZegoCopyrightedMusicGetSharedResourceResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetSharedResourceResult-class.md)>



Get shared music resource.  




##### [getStandardPitch](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getStandardPitch.md)(String resourceID) Future&lt;[ZegoCopyrightedMusicGetStandardPitchResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicGetStandardPitchResult-class.md)>



Get standard pitch data.  




##### [getTotalScore](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/getTotalScore.md)(String resourceID) Future&lt;int>



Get total score .  




##### [initCopyrightedMusic](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/initCopyrightedMusic.md)([ZegoCopyrightedMusicConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicConfig-class.md) config) Future&lt;[ZegoCopyrightedMusicInitResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicInitResult-class.md)>



Initialize the copyrighted music module.  




##### [noSuchMethod](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/noSuchMethod.md)(Invocation invocation) dynamic



Invoked when a non-existent method or property is accessed.  
_<span class="feature">inherited</span>_



##### [pauseScore](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/pauseScore.md)(String resourceID) Future&lt;int>



Pause scoring.  




##### [queryCache](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/queryCache.md)(String songID, [ZegoCopyrightedMusicType](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicType.md) type) Future&lt;bool>



Query the resource's cache is existed or not.  




##### [~~requestAccompaniment~~](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/requestAccompaniment.md)([ZegoCopyrightedMusicRequestConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestConfig-class.md) config) Future&lt;[ZegoCopyrightedMusicRequestAccompanimentResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestAccompanimentResult-class.md)>



<code>Deprecated</code> Request accompaniment. Deprecated since 3.0.2, please use the <a href="../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/requestResource.md">requestResource</a> function instead.  




##### [~~requestAccompanimentClip~~](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/requestAccompanimentClip.md)([ZegoCopyrightedMusicRequestConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestConfig-class.md) config) Future&lt;[ZegoCopyrightedMusicRequestAccompanimentClipResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestAccompanimentClipResult-class.md)>



<code>Deprecated</code> Request accompaniment clip. Deprecated since 3.0.2, please use the <a href="../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/requestResource.md">requestResource</a> function instead.  




##### [requestResource](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/requestResource.md)([ZegoCopyrightedMusicRequestConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestConfig-class.md) config, [ZegoCopyrightedMusicResourceType](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicResourceType.md) type) Future&lt;[ZegoCopyrightedMusicRequestResourceResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestResourceResult-class.md)>



Request music resource.  




##### [~~requestSong~~](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/requestSong.md)([ZegoCopyrightedMusicRequestConfig](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestConfig-class.md) config) Future&lt;[ZegoCopyrightedMusicRequestSongResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicRequestSongResult-class.md)>



<code>Deprecated</code> Request a song. Deprecated since 3.0.2, please use the <a href="../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/requestResource.md">requestResource</a> function instead.  




##### [resetScore](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/resetScore.md)(String resourceID) Future&lt;int>



Reset scoring.  




##### [resumeScore](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/resumeScore.md)(String resourceID) Future&lt;int>



Resume scoring.  




##### [sendExtendedRequest](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/sendExtendedRequest.md)(String command, String params) Future&lt;[ZegoCopyrightedMusicSendExtendedRequestResult](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusicSendExtendedRequestResult-class.md)>



Send extended feature request.  




##### [startScore](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/startScore.md)(String resourceID, int pitchValueInterval) Future&lt;int>



Start scoring.  




##### [stopScore](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/stopScore.md)(String resourceID) Future&lt;int>



Stop scoring.  




##### [toString](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/toString.md)() String



A string representation of this object.  
_<span class="feature">inherited</span>_





## Operators

##### [operator ==](../zego_uikit_prebuilt_live_audio_room/ZegoCopyrightedMusic/operator_equals.md)(Object other) bool



The equality operator.  
_<span class="feature">inherited</span>_















