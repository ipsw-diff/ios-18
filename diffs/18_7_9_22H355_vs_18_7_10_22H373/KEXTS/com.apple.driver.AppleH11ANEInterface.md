## com.apple.driver.AppleH11ANEInterface

> `com.apple.driver.AppleH11ANEInterface`

```diff

-8.600.2.0.0
+8.600.5.0.0
   __TEXT.__cstring: 0xa92a
-  __TEXT.__os_log: 0x3377c
+  __TEXT.__os_log: 0x338cc
   __TEXT.__const: 0x6d8
-  __TEXT_EXEC.__text: 0xa7e8c
+  __TEXT_EXEC.__text: 0xa7fd4
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x3948
   __DATA.__common: 0x3f0

   __DATA_CONST.__mod_init_func: 0xd8
   __DATA_CONST.__mod_term_func: 0x30
   __DATA_CONST.__const: 0x6890
-  __DATA_CONST.__kalloc_type: 0x2780
+  __DATA_CONST.__kalloc_type: 0x2840
   __DATA_CONST.__kalloc_var: 0x2e90
   Functions: 1803
   Symbols:   0
-  CStrings:  3505
+  CStrings:  3508
 
Functions:
~ sub_fffffff008c5e284 -> sub_fffffff008c5fc84 : 3976 -> 3892
~ sub_fffffff008c61550 -> sub_fffffff008c62efc : 26148 -> 26212
~ sub_fffffff008c6e410 -> sub_fffffff008c6fdfc : 420 -> 500
~ sub_fffffff008c86bc0 -> sub_fffffff008c885fc : 788 -> 1056
CStrings:
+ "ANE%d: %s: %s procID(%u) exceeds max\n"
+ "ANE%d: %s: Number of SNE ops exceeded max allowed: %u for procID: %d\n"
+ "ANE%d: %s: Total number of uncached IO > max allowed in auto-prewiring: %u\n"
```
