## apfs_condenser

> `/System/Library/Filesystems/apfs.fs/apfs_condenser`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.701.1
-  __TEXT.__text: 0x4c4a8
+2332.140.13.701.3
+  __TEXT.__text: 0x4c658
   __TEXT.__auth_stubs: 0x780
-  __TEXT.__cstring: 0xf743
+  __TEXT.__cstring: 0xf81e
   __TEXT.__const: 0x260
   __TEXT.__unwind_info: 0x808
   __DATA_CONST.__auth_got: 0x3c0

   - /usr/lib/libutil.dylib
   Functions: 659
   Symbols:   134
-  CStrings:  1266
+  CStrings:  1269
 
Functions:
~ sub_10000792c : 12332 -> 12340
~ sub_10000fa38 -> sub_10000fa40 : 1196 -> 1628
~ sub_10002ec98 -> sub_10002ee50 : 280 -> 272
CStrings:
+ "%s:%d: %s Invalid reap list free entry %d\n"
+ "%s:%d: %s reap list object 0x%llx first index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx free index %u larger than max index %u\n"
+ "%s:%d: %s reap list object 0x%llx last index %u larger than max index %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u + %u = %u\n"
+ "2332.140.13.701.3"
- "%s:%d: %s reap list object 0x%llx first index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx free index %u larger than max %u\n"
- "%s:%d: %s reap list object 0x%llx last index %u larger than max %u\n"
- "2332.140.13.701.1"
```
