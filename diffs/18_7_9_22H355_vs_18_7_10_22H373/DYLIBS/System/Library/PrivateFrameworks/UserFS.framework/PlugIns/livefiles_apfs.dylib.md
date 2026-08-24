## livefiles_apfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_apfs.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-2332.140.13.701.1
-  __TEXT.__text: 0xb3bf0
+2332.140.13.701.3
+  __TEXT.__text: 0xb3efc
   __TEXT.__auth_stubs: 0x8c0
   __TEXT.__const: 0x85a0
-  __TEXT.__oslogstring: 0x145e1
+  __TEXT.__oslogstring: 0x146bc
   __TEXT.__cstring: 0x4eb4
   __TEXT.__unwind_info: 0xf20
   __DATA_CONST.__got: 0x40

   - /usr/lib/libutil.dylib
   Functions: 2312
   Symbols:   1405
-  CStrings:  2051
+  CStrings:  2054
 
Functions:
~ _nx_check : 23860 -> 23868
~ _nx_reaper_checkpoint_traverse : 1632 -> 2404
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
