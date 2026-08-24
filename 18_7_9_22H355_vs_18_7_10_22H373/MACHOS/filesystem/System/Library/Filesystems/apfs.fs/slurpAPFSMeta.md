## slurpAPFSMeta

> `/System/Library/Filesystems/apfs.fs/slurpAPFSMeta`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.701.1
-  __TEXT.__text: 0x371b4
+2332.140.13.701.3
+  __TEXT.__text: 0x37364
   __TEXT.__auth_stubs: 0x830
-  __TEXT.__cstring: 0x9102
+  __TEXT.__cstring: 0x91cb
   __TEXT.__const: 0x200
   __TEXT.__unwind_info: 0x688
   __DATA_CONST.__auth_got: 0x418

   - /usr/lib/libSystem.B.dylib
   Functions: 520
   Symbols:   144
-  CStrings:  782
+  CStrings:  785
 
Functions:
~ sub_100031d94 : 1196 -> 1628
CStrings:
+ "%s:%d: %s Invalid reap list free entry %d\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u + %u = %u\n"
```
