## ActivitySharingDaemonCore

> `/System/Library/PrivateFrameworks/ActivitySharingDaemonCore.framework/ActivitySharingDaemonCore`

```diff

-824.7.1.0.0
-  __TEXT.__text: 0x7cef0
+824.7.2.0.0
+  __TEXT.__text: 0x7cf94
   __TEXT.__auth_stubs: 0xf30
   __TEXT.__objc_methlist: 0x4764
   __TEXT.__const: 0x1d8
   __TEXT.__cstring: 0x2e07
   __TEXT.__gcc_except_tab: 0x1050
-  __TEXT.__oslogstring: 0xe8d2
+  __TEXT.__oslogstring: 0xe924
   __TEXT.__unwind_info: 0x1bf8
   __TEXT.__objc_classname: 0xa67
   __TEXT.__objc_methname: 0x1155d

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2359
+  Functions: 2360
   Symbols:   5584
-  CStrings:  3957
+  CStrings:  3958
 
Symbols:
+ GCC_except_table243
- GCC_except_table242
Functions:
~ ___126-[ASRelationshipManager messageCenter:didReceiveFinalizeHandshake:fromSenderAddress:receiverAddress:messageHandledCompletion:]_block_invoke : 756 -> 808
+ ___126-[ASRelationshipManager messageCenter:didReceiveFinalizeHandshake:fromSenderAddress:receiverAddress:messageHandledCompletion:]_block_invoke.cold.2
CStrings:
+ "RelationshipManager not finalizing, accept has not been sent for relationship: %@"
```
