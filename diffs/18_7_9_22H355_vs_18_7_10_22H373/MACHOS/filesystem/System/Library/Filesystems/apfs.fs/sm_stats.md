## sm_stats

> `/System/Library/Filesystems/apfs.fs/sm_stats`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.701.1
-  __TEXT.__text: 0x43c38
+2332.140.13.701.3
+  __TEXT.__text: 0x43df0
   __TEXT.__auth_stubs: 0x720
-  __TEXT.__cstring: 0xce7e
+  __TEXT.__cstring: 0xcf59
   __TEXT.__const: 0x218
   __TEXT.__unwind_info: 0x700
   __DATA_CONST.__auth_got: 0x390

   - /usr/lib/libutil.dylib
   Functions: 576
   Symbols:   128
-  CStrings:  1056
+  CStrings:  1059
 
Functions:
~ sub_100005394 : 1196 -> 1628
~ sub_10002ca5c -> sub_10002cc0c : 12332 -> 12340
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
