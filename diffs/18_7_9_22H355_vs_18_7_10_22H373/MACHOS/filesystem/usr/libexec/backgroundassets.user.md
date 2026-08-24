## backgroundassets.user

> `/usr/libexec/backgroundassets.user`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-186.100.4.0.0
-  __TEXT.__text: 0x375cc
-  __TEXT.__auth_stubs: 0xbc0
+186.100.4.701.1
+  __TEXT.__text: 0x37810
+  __TEXT.__auth_stubs: 0xbd0
   __TEXT.__objc_stubs: 0x6f80
   __TEXT.__objc_methlist: 0x318c
   __TEXT.__const: 0x1c0
-  __TEXT.__oslogstring: 0x42b3
-  __TEXT.__cstring: 0x3862
+  __TEXT.__oslogstring: 0x4307
+  __TEXT.__cstring: 0x3872
   __TEXT.__objc_classname: 0x6c5
   __TEXT.__objc_methname: 0x8f85
   __TEXT.__objc_methtype: 0x18c5
   __TEXT.__gcc_except_tab: 0x14c8
-  __TEXT.__unwind_info: 0xe08
-  __DATA_CONST.__auth_got: 0x5f0
-  __DATA_CONST.__got: 0x380
+  __TEXT.__unwind_info: 0xe10
+  __DATA_CONST.__auth_got: 0x5f8
+  __DATA_CONST.__got: 0x388
   __DATA_CONST.__const: 0x10f0
   __DATA_CONST.__cfstring: 0x2100
   __DATA_CONST.__objc_classlist: 0x150

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/liblockdown.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1316
-  Symbols:   309
-  CStrings:  2289
+  Functions: 1318
+  Symbols:   311
+  CStrings:  2291
 
Symbols:
+ _SANDBOX_CHECK_NO_REPORT
+ _sandbox_check_by_audit_token
CStrings:
+ "BACallerHasFileAccessForURL: sandbox_check_by_audit_token denied write access to %s"
+ "file-write-data"
```
