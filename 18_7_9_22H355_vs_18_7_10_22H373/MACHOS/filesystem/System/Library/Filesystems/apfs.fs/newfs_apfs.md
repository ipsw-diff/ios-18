## newfs_apfs

> `/System/Library/Filesystems/apfs.fs/newfs_apfs`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.701.1
-  __TEXT.__text: 0x51974
+2332.140.13.701.3
+  __TEXT.__text: 0x51b34
   __TEXT.__auth_stubs: 0x830
-  __TEXT.__cstring: 0xfde9
+  __TEXT.__cstring: 0xfec4
   __TEXT.__const: 0x8360
   __TEXT.__unwind_info: 0x858
   __DATA_CONST.__auth_got: 0x418

   - /usr/lib/libutil.dylib
   Functions: 706
   Symbols:   146
-  CStrings:  1334
+  CStrings:  1337
 
Functions:
~ sub_100005b4c : 12332 -> 12340
~ sub_10000f390 -> sub_10000f398 : 1196 -> 1628
~ sub_100034670 -> sub_100034828 : 272 -> 280
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
