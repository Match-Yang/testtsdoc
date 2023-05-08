


# beginRoomPropertiesBatchOperation method







- @override

void beginRoomPropertiesBatchOperation
({required String roomID, bool isForce = false, bool isDeleteAfterOwnerLeft = false, bool isUpdateOwner = false})

_<span class="feature">override</span>_



<p>begin room properties batch operation</p>



## Implementation

```dart
@override
void beginRoomPropertiesBatchOperation({
  required String roomID,
  bool isForce = false,
  bool isDeleteAfterOwnerLeft = false,
  bool isUpdateOwner = false,
}) {
  ZIM.getInstance()!.beginRoomAttributesBatchOperation(
        roomID,
        ZIMRoomAttributesBatchOperationConfig()
          ..isForce = isForce
          ..isDeleteAfterOwnerLeft = isDeleteAfterOwnerLeft
          ..isUpdateOwner = isUpdateOwner,
      );
}
```







