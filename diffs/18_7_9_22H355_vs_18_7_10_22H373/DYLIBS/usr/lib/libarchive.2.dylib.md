## libarchive.2.dylib

> `/usr/lib/libarchive.2.dylib`

```diff

-151.140.2.702.1
-  __TEXT.__text: 0xe1e7c
+151.140.2.702.3
+  __TEXT.__text: 0xe1ebc
   __TEXT.__auth_stubs: 0x10d0
   __TEXT.__const: 0x933c
-  __TEXT.__cstring: 0x9dbc
+  __TEXT.__cstring: 0x9ddd
   __TEXT.__unwind_info: 0xba8
   __DATA_CONST.__got: 0x30
   __DATA_CONST.__const: 0x1a10

   - /usr/lib/libz.1.dylib
   Functions: 2238
   Symbols:   2513
-  CStrings:  1823
+  CStrings:  1824
 
Functions:
~ _cab_read_ahead_cfdata_lzx : 1204 -> 1272
~ _make_fflags_entry : 792 -> 656
~ _hfs_write_decmpfs_block : 1084 -> 1088
~ _parse_codes : 3888 -> 3920
~ _copy_from_lzss_window : 312 -> 380
~ _parse_filter : 1792 -> 1820
CStrings:
+ "Invalid CFDATA uncompressed size"
```
