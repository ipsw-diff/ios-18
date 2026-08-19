## fskitd

> `/usr/libexec/fskitd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-531.140.9.0.3
-  __TEXT.__text: 0x40fc0
+531.140.9.700.1
+  __TEXT.__text: 0x40fd4
   __TEXT.__auth_stubs: 0xb10
   __TEXT.__objc_stubs: 0x46e0
-  __TEXT.__objc_methlist: 0x1d94
+  __TEXT.__objc_methlist: 0x1da4
   __TEXT.__const: 0x130
   __TEXT.__gcc_except_tab: 0x2004
   __TEXT.__cstring: 0x27b4
   __TEXT.__oslogstring: 0x3417
-  __TEXT.__objc_classname: 0x21a
+  __TEXT.__objc_classname: 0x232
   __TEXT.__objc_methname: 0x5503
   __TEXT.__objc_methtype: 0x1fc9
   __TEXT.__unwind_info: 0xf30

   __DATA_CONST.__const: 0x1fe8
   __DATA_CONST.__cfstring: 0x820
   __DATA_CONST.__objc_classlist: 0x88
-  __DATA_CONST.__objc_protolist: 0x48
+  __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_protorefs: 0x10
+  __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x60
   __DATA_CONST.__objc_intobj: 0x18
-  __DATA.__objc_const: 0x1ff8
+  __DATA.__objc_const: 0x2028
   __DATA.__objc_selrefs: 0x1580
   __DATA.__objc_ivar: 0x170
   __DATA.__objc_data: 0x550
-  __DATA.__data: 0x6c0
+  __DATA.__data: 0x720
   __DATA.__common: 0x74
   __DATA.__bss: 0x31
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libutil.dylib
   Functions: 1220
   Symbols:   292
-  CStrings:  1754
+  CStrings:  1755
 
Functions:
~ sub_10000da94 : 808 -> 828
CStrings:
+ "LiveFSMounterUnentitled"
```
