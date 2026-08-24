## apfs_checkseal

> `/System/Library/Filesystems/apfs.fs/apfs_checkseal`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.701.1
-  __TEXT.__text: 0x4f174
+2332.140.13.701.3
+  __TEXT.__text: 0x4f32c
   __TEXT.__auth_stubs: 0x750
   __TEXT.__const: 0x510
-  __TEXT.__cstring: 0x10058
+  __TEXT.__cstring: 0x10133
   __TEXT.__unwind_info: 0x8d8
   __DATA_CONST.__auth_got: 0x3a8
   __DATA_CONST.__got: 0x50

   - /usr/lib/libutil.dylib
   Functions: 722
   Symbols:   131
-  CStrings:  1293
+  CStrings:  1296
 
Functions:
~ sub_10002a314 : 1196 -> 1628
~ sub_10002ca60 -> sub_10002cc10 : 12332 -> 12340
CStrings:
+ "%s:%d: %s Invalid reap list free entry %d\n"
+ "%s:%d: %s reap list object 0x%llx first index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx free index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx last index %u larger than max index %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u + %u = %u\n"
- "%s:%d: %s reap list object 0x%llx first index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx free index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx last index %u larger than max %u\n"
```
