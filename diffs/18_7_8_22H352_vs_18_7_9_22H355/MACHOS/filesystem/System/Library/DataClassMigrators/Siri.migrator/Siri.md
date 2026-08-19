## Siri

> `/System/Library/DataClassMigrators/Siri.migrator/Siri`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-3406.16.1.0.0
-  __TEXT.__text: 0x2e88
+3406.16.1.1.1
+  __TEXT.__text: 0x2ff8
   __TEXT.__auth_stubs: 0x360
-  __TEXT.__objc_stubs: 0x8a0
-  __TEXT.__objc_methlist: 0x11c
+  __TEXT.__objc_stubs: 0x8c0
+  __TEXT.__objc_methlist: 0x128
   __TEXT.__const: 0x1c
-  __TEXT.__cstring: 0x61a
-  __TEXT.__oslogstring: 0x4df
+  __TEXT.__cstring: 0x69a
+  __TEXT.__oslogstring: 0x502
   __TEXT.__objc_classname: 0xd
-  __TEXT.__objc_methname: 0x6a7
+  __TEXT.__objc_methname: 0x6e4
   __TEXT.__objc_methtype: 0x20
-  __TEXT.__unwind_info: 0xa8
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__auth_got: 0x1b8
   __DATA_CONST.__got: 0xf0
   __DATA_CONST.__const: 0x10
-  __DATA_CONST.__cfstring: 0x4c0
+  __DATA_CONST.__cfstring: 0x4e0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_intobj: 0x48
   __DATA.__objc_const: 0x90
-  __DATA.__objc_selrefs: 0x248
+  __DATA.__objc_selrefs: 0x250
   __DATA.__objc_data: 0x50
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 26
+  Functions: 27
   Symbols:   96
-  CStrings:  162
+  CStrings:  166
 
CStrings:
+ "%s No history to remove. Skipping."
+ "-[SiriMigrator _performRemoveAnnounceNotificationsThreadCancellationHistory]"
+ "Announce Notifications Thread Cancellation History"
+ "_performRemoveAnnounceNotificationsThreadCancellationHistory"
```
