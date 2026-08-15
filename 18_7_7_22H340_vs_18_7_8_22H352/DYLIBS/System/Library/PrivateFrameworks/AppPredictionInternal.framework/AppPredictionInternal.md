## AppPredictionInternal

> `/System/Library/PrivateFrameworks/AppPredictionInternal.framework/AppPredictionInternal`

```diff

-588.12.0.0.0
-  __TEXT.__text: 0x43c65c
+588.12.0.1.0
+  __TEXT.__text: 0x43c7f0
   __TEXT.__auth_stubs: 0x31f0
-  __TEXT.__objc_methlist: 0x381dc
+  __TEXT.__objc_methlist: 0x381ec
   __TEXT.__const: 0x2e72
   __TEXT.__cstring: 0x57a72
-  __TEXT.__oslogstring: 0x3a056
+  __TEXT.__oslogstring: 0x3a0c6
   __TEXT.__gcc_except_tab: 0xeed0
   __TEXT.__dlopen_cstrs: 0x23c
   __TEXT.__ustring: 0x90

   __TEXT.__swift_as_entry: 0xc8
   __TEXT.__swift_as_ret: 0xb4
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0xd908
+  __TEXT.__unwind_info: 0xd910
   __TEXT.__eh_frame: 0x1bd4
   __TEXT.__objc_classname: 0x8b6b
-  __TEXT.__objc_methname: 0xac656
+  __TEXT.__objc_methname: 0xac67d
   __TEXT.__objc_methtype: 0x19545
-  __TEXT.__objc_stubs: 0x4c4c0
-  __DATA_CONST.__got: 0x3670
+  __TEXT.__objc_stubs: 0x4c4e0
+  __DATA_CONST.__got: 0x3678
   __DATA_CONST.__const: 0xb8f0
   __DATA_CONST.__objc_classlist: 0x1f00
   __DATA_CONST.__objc_catlist: 0x128
   __DATA_CONST.__objc_protolist: 0x4b0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1b918
+  __DATA_CONST.__objc_selrefs: 0x1b920
   __DATA_CONST.__objc_protorefs: 0xa8
   __DATA_CONST.__objc_superrefs: 0x1500
   __DATA_CONST.__objc_arraydata: 0x1370

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 24623
-  Symbols:   45825
-  CStrings:  32948
+  Functions: 24624
+  Symbols:   45827
+  CStrings:  32950
 
Symbols:
+ -[ATXNotificationAndSuggestionDatabase _purgeNotificationBiomeStreamsIfNeeded]
+ GCC_except_table173
+ GCC_except_table178
+ __kATXBiomeNotificationPurgeCompleteKey
+ _objc_msgSend$_purgeNotificationBiomeStreamsIfNeeded
- GCC_except_table172
- GCC_except_table177
- GCC_except_table82
Functions:
~ -[ATXNotificationAndSuggestionDatabase init] : 152 -> 160
+ -[ATXNotificationAndSuggestionDatabase _purgeNotificationBiomeStreamsIfNeeded]
~ -[ATXNotificationsLoggingServer logNotificationEvent:notification:reason:interactionUI:] : 1152 -> 1288
CStrings:
+ "ATXNotificationAndSuggestionDatabase: Purging private notification streams to remove persisted text content"
+ "_purgeNotificationBiomeStreamsIfNeeded"
```
