## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/APFS`

```diff

-2332.140.13.701.1
-  __TEXT.__text: 0x4fd90
+2332.140.13.701.3
+  __TEXT.__text: 0x4ff40
   __TEXT.__auth_stubs: 0xb30
   __TEXT.__const: 0x8410
-  __TEXT.__cstring: 0xde96
+  __TEXT.__cstring: 0xdf71
   __TEXT.__oslogstring: 0xa81
   __TEXT.__gcc_except_tab: 0x18
   __TEXT.__unwind_info: 0x930

   - /usr/lib/libutil.dylib
   Functions: 797
   Symbols:   1035
-  CStrings:  1306
+  CStrings:  1309
 
Functions:
~ _nx_check : 12316 -> 12324
~ _nx_reaper_checkpoint_traverse : 1192 -> 1624
~ _bitmap_count_bits : 300 -> 292
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
