## libsystem_c_debug.dylib

> `/System/DriverKit/usr/lib/system/libsystem_c_debug.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__AUTH.__data`
- `__DATA.__data`

```diff

-1698.140.3.703.1
-  __TEXT.__text: 0xbf91c
+1698.140.3.703.2
+  __TEXT.__text: 0xbffbc
   __TEXT.__auth_stubs: 0xc00
   __TEXT.__const: 0x27dc
-  __TEXT.__cstring: 0x2ebb
+  __TEXT.__cstring: 0x2ee5
   __TEXT.__unwind_info: 0x9a8
   __DATA_CONST.__got: 0x20
-  __DATA_CONST.__const: 0x13a8
+  __DATA_CONST.__const: 0x13c0
   __AUTH_CONST.__auth_got: 0x600
   __AUTH.__data: 0x288
   __AUTH.__constrw: 0x80

   - /System/DriverKit/usr/lib/system/libsystem_pthread.dylib
   Functions: 1704
   Symbols:   2212
-  CStrings:  827
+  CStrings:  829
 
Symbols:
+ _tre_compute_npfl
+ _tre_stack_num_items
- _tre_compute_nfl
- _tre_stack_num_objects
Functions:
~ _regncomp_l : 756 -> 784
~ _regcomp_l : 172 -> 260
~ _regwncomp_l : 140 -> 180
~ _regwcomp_l : 160 -> 224
~ _regwcomp : 84 -> 200
~ _tre_match : 832 -> 824
~ _tre_ast_new_literal : 156 -> 152
~ _tre_compile : 3580 -> 3764
~ _tre_add_tags : 11468 -> 11500
~ _tre_expand_ast : 2280 -> 2208
~ _tre_compute_nfl -> _tre_compute_npfl : 3408 -> 3460
~ _tre_add_tag_right : 364 -> 360
~ _tre_add_tag_left : 364 -> 360
~ _tre_copy_ast : 1696 -> 1756
~ _tre_tnfa_run_backtrack : 7932 -> 8028
~ _tre_tnfa_run_parallel : 7040 -> 7876
~ _tre_parse : 10064 -> 10116
~ _tre_parse_bound : 1048 -> 1080
~ _tre_parse_bracket : 1628 -> 1588
~ _tre_expand_macro : 344 -> 348
~ _tre_parse_int : 220 -> 392
~ _tre_parse_bracket_items : 3040 -> 3036
~ _tre_stack_new : 220 -> 204
~ _tre_stack_pop_int : 56 -> 48
CStrings:
+ "REG_BADMAX"
+ "maximum repetition exceeds 255"
```
