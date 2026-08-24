## apfs_vol_converter

> `/System/Library/Filesystems/apfs.fs/apfs_vol_converter`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.701.1
-  __TEXT.__text: 0x57240
+2332.140.13.701.3
+  __TEXT.__text: 0x573f8
   __TEXT.__auth_stubs: 0x9e0
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x11896
+  __TEXT.__cstring: 0x11971
   __TEXT.__const: 0x2c0
   __TEXT.__gcc_except_tab: 0x570
   __TEXT.__unwind_info: 0xb98

   - /usr/lib/libutil.dylib
   Functions: 837
   Symbols:   183
-  CStrings:  1578
+  CStrings:  1581
 
Functions:
~ sub_10003ace4 : 1196 -> 1628
~ sub_10003d430 -> sub_10003d5e0 : 12332 -> 12340
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
