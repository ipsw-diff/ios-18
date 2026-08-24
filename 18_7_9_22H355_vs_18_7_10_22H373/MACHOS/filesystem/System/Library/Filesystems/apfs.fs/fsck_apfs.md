## fsck_apfs

> `/System/Library/Filesystems/apfs.fs/fsck_apfs`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.701.1
-  __TEXT.__text: 0x4cb74
+2332.140.13.701.3
+  __TEXT.__text: 0x4cc14
   __TEXT.__auth_stubs: 0x930
-  __TEXT.__cstring: 0x187bc
+  __TEXT.__cstring: 0x18885
   __TEXT.__const: 0x84a4
-  __TEXT.__unwind_info: 0xa30
+  __TEXT.__unwind_info: 0xa28
   __DATA_CONST.__auth_got: 0x498
   __DATA_CONST.__got: 0x68
   __DATA_CONST.__auth_ptr: 0x48
   __DATA_CONST.__const: 0x560
   __DATA_CONST.__cfstring: 0x200
   __DATA.__data: 0xed4
-  __DATA.__bss: 0x1c864
-  __DATA.__common: 0xab1
+  __DATA.__bss: 0x1c86c
+  __DATA.__common: 0x791
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libutil.dylib
   Functions: 824
   Symbols:   164
-  CStrings:  1850
+  CStrings:  1852
 
Functions:
~ sub_100021c90 : 404 -> 92
~ sub_100021e24 -> sub_100021cec : 776 -> 404
~ sub_10002212c -> sub_100021e80 : 1656 -> 948
~ sub_1000227a4 -> sub_100022234 : 96 -> 1656
~ sub_10003bbb8 -> sub_10003bc60 : 1416 -> 1408
CStrings:
+ "2332.140.13.701.3"
+ "could not allocate array of %u entries for tracking omap objects in reap list; skipping subsequent ones\n"
+ "encountered more than %u omap objects in reap list; skipping subsequent ones\n"
+ "reap list object 0x%llx first index %u larger than max index %u\n"
+ "reap list object 0x%llx free index %u larger than max index %u\n"
+ "reap list object 0x%llx last index %u larger than max index %u\n"
- "2332.140.13.701.1"
- "reap list object 0x%llx first index %u larger than max %u\n"
- "reap list object 0x%llx free index %u larger than max %u\n"
- "reap list object 0x%llx last index %u larger than max %u\n"
```
