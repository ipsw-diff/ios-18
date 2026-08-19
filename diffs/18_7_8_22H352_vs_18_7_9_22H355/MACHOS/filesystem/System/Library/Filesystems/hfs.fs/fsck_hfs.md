## fsck_hfs

> `/System/Library/Filesystems/hfs.fs/fsck_hfs`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-683.120.3.700.2
-  __TEXT.__text: 0x301a8
+683.120.3.702.1
+  __TEXT.__text: 0x301e4
   __TEXT.__auth_stubs: 0x770
   __TEXT.__const: 0x112c
-  __TEXT.__cstring: 0x6e38
+  __TEXT.__cstring: 0x6e94
   __TEXT.__unwind_info: 0x508
   __DATA_CONST.__auth_got: 0x3b8
   __DATA_CONST.__got: 0x50

   - /usr/lib/libSystem.B.dylib
   Functions: 468
   Symbols:   134
-  CStrings:  784
+  CStrings:  786
 
Functions:
~ sub_100021f80 : 1124 -> 1132
~ sub_1000223e4 -> sub_1000223ec : 656 -> 652
~ sub_10002d538 -> sub_10002d53c : 3420 -> 3476
CStrings:
+ "Physical block size cannot be greater than 16 KiB\n"
+ "Physical block size is not a power of 2\n"
```
