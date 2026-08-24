## profiled

> `/usr/libexec/profiled`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2400.5.6.0.0
-  __TEXT.__text: 0x9f4f0
-  __TEXT.__auth_stubs: 0x2230
+2400.5.6.700.1
+  __TEXT.__text: 0x9f4f4
+  __TEXT.__auth_stubs: 0x2240
   __TEXT.__objc_stubs: 0xfbe0
   __TEXT.__objc_methlist: 0x56e4
   __TEXT.__const: 0x1fc

   __TEXT.__objc_classname: 0xb36
   __TEXT.__objc_methtype: 0x205a
   __TEXT.__unwind_info: 0x16b0
-  __DATA_CONST.__auth_got: 0x1128
+  __DATA_CONST.__auth_got: 0x1130
   __DATA_CONST.__got: 0x1bb8
   __DATA_CONST.__const: 0x1b50
   __DATA_CONST.__cfstring: 0x8540

   - /usr/lib/libmis.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 2025
-  Symbols:   1480
+  Symbols:   1481
   CStrings:  4898
 
Symbols:
+ _MCIsSystemLockdownModeEnabled
Functions:
~ sub_100045bcc : 1340 -> 1336
~ sub_10008757c -> sub_100087578 : 140 -> 148
```
