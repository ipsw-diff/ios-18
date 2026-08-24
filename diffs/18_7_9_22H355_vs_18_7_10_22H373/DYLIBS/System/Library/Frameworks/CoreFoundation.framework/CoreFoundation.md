## CoreFoundation

> `/System/Library/Frameworks/CoreFoundation.framework/CoreFoundation`

```diff

-3603.1.104.0.0
-  __TEXT.__text: 0x1b7aec
+3603.1.107.0.0
+  __TEXT.__text: 0x1b7c38
   __TEXT.__auth_stubs: 0x31b0
   __TEXT.__init_offsets: 0x4
-  __TEXT.__objc_methlist: 0x76ec
+  __TEXT.__objc_methlist: 0x76fc
   __TEXT.__const: 0x19b440
-  __TEXT.__oslogstring: 0x5679
+  __TEXT.__oslogstring: 0x56a8
   __TEXT.__cstring: 0x14ae38
   __TEXT.__gcc_except_tab: 0x44c0
   __TEXT.__ustring: 0x484
   __TEXT.__dof_CFRunLoop: 0x964
   __TEXT.__dof_Cocoa_Aut: 0x486
-  __TEXT.__unwind_info: 0x5dc0
+  __TEXT.__unwind_info: 0x5dd0
   __TEXT.__eh_frame: 0x59c
   __TEXT.__objc_classname: 0xa7c
   __TEXT.__objc_methname: 0x7fba

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 7866
-  Symbols:   12062
-  CStrings:  59643
+  Functions: 7868
+  Symbols:   12063
+  CStrings:  59644
 
Symbols:
+ -[NSNull hash]
Functions:
~ -[CFPDSource copyPropertyListWithoutDrainingPendingChangesValidatingPlist:andReturnFileUID:andMode:] : 1324 -> 1356
~ -[CFPDSource openActualPath] : 164 -> 320
+ -[NSNull initWithCoder:]
~ _OUTLINED_FUNCTION_1 : 20 -> 24
~ _OUTLINED_FUNCTION_2 : 24 -> 20
~ _OUTLINED_FUNCTION_3 : 24 -> 16
~ _OUTLINED_FUNCTION_5 : 16 -> 24
~ _OUTLINED_FUNCTION_6 : 16 -> 12
~ _OUTLINED_FUNCTION_8 : 12 -> 16
~ -[CFPDSource copyPropertyListWithoutDrainingPendingChangesValidatingPlist:andReturnFileUID:andMode:].cold.2 : 120 -> 136
~ -[CFPDSource copyPropertyListWithoutDrainingPendingChangesValidatingPlist:andReturnFileUID:andMode:].cold.3 : 44 -> 120
+ -[CFPDSource copyPropertyListWithoutDrainingPendingChangesValidatingPlist:andReturnFileUID:andMode:].cold.4
CStrings:
+ "The file could not be opened: %{darwin.errno}d"
```
