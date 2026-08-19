## assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_floatobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3406.16.1.0.0
-  __TEXT.__text: 0x36dba0
-  __TEXT.__auth_stubs: 0x34c0
-  __TEXT.__objc_stubs: 0x456c0
-  __TEXT.__objc_methlist: 0x225e0
-  __TEXT.__const: 0x10990
+3406.16.1.1.1
+  __TEXT.__text: 0x36d928
+  __TEXT.__auth_stubs: 0x34a0
+  __TEXT.__objc_stubs: 0x45680
+  __TEXT.__objc_methlist: 0x225d0
+  __TEXT.__const: 0x10ac0
   __TEXT.__dlopen_cstrs: 0xafa
   __TEXT.__gcc_except_tab: 0x4888
-  __TEXT.__cstring: 0x5199a
-  __TEXT.__oslogstring: 0x3f9ab
+  __TEXT.__cstring: 0x51948
+  __TEXT.__oslogstring: 0x3f973
   __TEXT.__objc_classname: 0x51bf
-  __TEXT.__objc_methname: 0x5d461
+  __TEXT.__objc_methname: 0x5d3ff
   __TEXT.__objc_methtype: 0xf21b
   __TEXT.__ustring: 0x2b0
-  __TEXT.__unwind_info: 0xa3b0
+  __TEXT.__unwind_info: 0xa3a8
   __TEXT.__eh_frame: 0xe58
-  __DATA_CONST.__auth_got: 0x1a70
+  __DATA_CONST.__auth_got: 0x1a60
   __DATA_CONST.__got: 0x3b20
   __DATA_CONST.__auth_ptr: 0x20
-  __DATA_CONST.__const: 0x14c88
+  __DATA_CONST.__const: 0x14c68
   __DATA_CONST.__cfstring: 0x12b20
   __DATA_CONST.__objc_classlist: 0xd20
   __DATA_CONST.__objc_catlist: 0x630

   __DATA_CONST.__objc_doubleobj: 0x30
   __DATA_CONST.__objc_floatobj: 0x30
   __DATA.__objc_const: 0x33870
-  __DATA.__objc_selrefs: 0x14900
+  __DATA.__objc_selrefs: 0x148f0
   __DATA.__objc_ivar: 0x25a0
   __DATA.__objc_data: 0x8340
   __DATA.__data: 0x60f8

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 14338
-  Symbols:   2890
-  CStrings:  26806
+  Functions: 14336
+  Symbols:   2888
+  CStrings:  26801
 
Symbols:
- __AFPreferencesAnnounceNotificationThreadCancellationStaleThreshold
- __AFPreferencesRemoveThreadCancellationsOlderThanTimeInterval
CStrings:
+ "MobileAssistantDaemons-3406.16.1.1.1"
- "%s Marking thread cancellation for app: %@ threadID: %@"
- "-[ADExternalNotificationRequestHandler _markThreadCancellationForCurrentRequest:]"
- "736"
- "MobileAssistantDaemons-3406.16.1"
- "_markThreadCancellationForCurrentRequest:"
- "markLastAnnouncementInThreadAsCancelledForApp:threadID:"
```
