## replayd

> `/usr/libexec/replayd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-630.4.101.1.0
-  __TEXT.__text: 0x542d0
+630.4.101.2.0
+  __TEXT.__text: 0x543d0
   __TEXT.__auth_stubs: 0xf10
-  __TEXT.__objc_stubs: 0x7700
+  __TEXT.__objc_stubs: 0x7740
   __TEXT.__objc_methlist: 0x3e0c
   __TEXT.__const: 0x194
-  __TEXT.__objc_methname: 0xb23d
-  __TEXT.__cstring: 0xb0f8
-  __TEXT.__oslogstring: 0x7fb0
+  __TEXT.__objc_methname: 0xb242
+  __TEXT.__cstring: 0xb12d
+  __TEXT.__oslogstring: 0x7ff5
   __TEXT.__objc_classname: 0x635
   __TEXT.__objc_methtype: 0x1ce7
   __TEXT.__gcc_except_tab: 0x6e8
-  __TEXT.__unwind_info: 0x10c8
+  __TEXT.__unwind_info: 0x10d0
   __DATA_CONST.__auth_got: 0x798
-  __DATA_CONST.__got: 0x5c0
+  __DATA_CONST.__got: 0x5c8
   __DATA_CONST.__const: 0x1638
   __DATA_CONST.__cfstring: 0x3460
   __DATA_CONST.__objc_classlist: 0x160

   __DATA_CONST.__objc_intobj: 0x258
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA.__objc_const: 0x8c70
-  __DATA.__objc_selrefs: 0x2618
+  __DATA.__objc_selrefs: 0x2620
   __DATA.__objc_ivar: 0x4f0
   __DATA.__objc_data: 0xdc0
   __DATA.__data: 0xa38

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1760
-  Symbols:   438
-  CStrings:  3576
+  Functions: 1761
+  Symbols:   439
+  CStrings:  3579
 
Symbols:
+ _OBJC_CLASS_$_NSNull
Functions:
~ sub_10002b9bc : 48 -> 176
+ sub_10005202c
CStrings:
+ " [ERROR] %{public}s:%d Empty extensionToken attempted to be consumed"
+ "-[RPConnectionManager consumeSandboxExtensionToken:]"
+ "null"
```
