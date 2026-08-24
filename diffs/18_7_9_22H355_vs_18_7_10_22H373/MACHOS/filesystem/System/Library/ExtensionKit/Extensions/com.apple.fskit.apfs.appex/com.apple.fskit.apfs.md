## com.apple.fskit.apfs

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.apfs.appex/com.apple.fskit.apfs`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2332.140.13.701.1
-  __TEXT.__text: 0x5fa94
+2332.140.13.701.3
+  __TEXT.__text: 0x5fc40
   __TEXT.__auth_stubs: 0xad0
   __TEXT.__objc_stubs: 0x4e0
   __TEXT.__objc_methlist: 0x1d4
-  __TEXT.__cstring: 0x14f2f
+  __TEXT.__cstring: 0x1500a
   __TEXT.__const: 0x84c8
   __TEXT.__gcc_except_tab: 0x14
   __TEXT.__oslogstring: 0xd1

   - /usr/lib/libutil.dylib
   Functions: 1190
   Symbols:   714
-  CStrings:  1951
+  CStrings:  1954
 
Functions:
~ _nx_reaper_checkpoint_traverse : 1248 -> 1668
~ _nx_check : 12316 -> 12324
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
