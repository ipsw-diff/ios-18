## bluetoothd

> `/usr/sbin/bluetoothd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-186.4.1.1.0
-  __TEXT.__text: 0x7c7210
+186.4.1.2.0
+  __TEXT.__text: 0x7c73fc
   __TEXT.__auth_stubs: 0x4620
   __TEXT.__objc_stubs: 0x13140
   __TEXT.__init_offsets: 0x54
   __TEXT.__objc_methlist: 0x655c
   __TEXT.__const: 0xa77c
   __TEXT.__gcc_except_tab: 0x61ab4
-  __TEXT.__cstring: 0xa303b
+  __TEXT.__cstring: 0xa30c0
   __TEXT.__objc_classname: 0x7eb
   __TEXT.__objc_methname: 0x15ebb
   __TEXT.__objc_methtype: 0x44e7
   __TEXT.__oslogstring: 0xa1bb7
   __TEXT.__ustring: 0x34
   __TEXT.__dlopen_cstrs: 0x64
-  __TEXT.__unwind_info: 0x1fbe8
+  __TEXT.__unwind_info: 0x1fbf0
   __TEXT.__eh_frame: 0x60
   __DATA_CONST.__auth_got: 0x2328
   __DATA_CONST.__got: 0xc90

   - /usr/lib/libsqlite3.dylib
   Functions: 30494
   Symbols:   1547
-  CStrings:  35485
+  CStrings:  35488
 
Functions:
~ sub_1002304d0 : 580 -> 652
~ sub_100230818 -> sub_100230860 : 160 -> 224
~ sub_1002388c0 -> sub_100238948 : 336 -> 464
~ sub_100238d28 -> sub_100238e30 : 1020 -> 1012
~ sub_1002752c8 -> sub_1002753c8 : 164 -> 260
~ sub_10027536c -> sub_1002754cc : 160 -> 300
CStrings:
+ "18:55:22"
+ "Invalid MPS value %d, minimum required is 23"
+ "Jul 24 2026"
+ "L2CAPAGG RX: Connection freed during packet processing, stopping."
+ "channel already freed"
- "21:18:58"
- "Apr 29 2026"
```
