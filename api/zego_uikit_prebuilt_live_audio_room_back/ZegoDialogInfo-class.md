

# ZegoDialogInfo class

<p>对话框信息。用于控制某些功能是否显示对话框，比如离开语聊房前是否需要显示确认对话框。</p>

## Constructors

`ZegoDialogInfo` ({required String title, required String message, String cancelButtonName = 'Cancel', String confirmButtonName = 'OK'})

## Properties

##### `cancelButtonName` &#8596; String

取消按钮上的文本内容，默认为 'Cancel'  
_<span class="feature">read / write</span>_

##### `confirmButtonName` &#8596; String

确认按钮上的文本内容，默认为 'OK'  
_<span class="feature">read / write</span>_


##### `message` &#8594; String

对话框的文本内容  
_<span class="feature">final</span>_


##### `title` &#8594; String

对话框的标题  
_<span class="feature">final</span>_
