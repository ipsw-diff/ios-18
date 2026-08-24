## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-803.73.1.0.0
-  __TEXT.__text: 0x56ac8
+803.73.3.0.0
+  __TEXT.__text: 0x56cb4
   __TEXT.__auth_stubs: 0xce0
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0x8
-  __TEXT.__cstring: 0x1f096
+  __TEXT.__cstring: 0x1f18f
   __TEXT.__const: 0x118f8
   __TEXT.__gcc_except_tab: 0x490
   __TEXT.__objc_methname: 0xb
-  __TEXT.__unwind_info: 0x580
+  __TEXT.__unwind_info: 0x588
   __DATA_CONST.__auth_got: 0x680
   __DATA_CONST.__got: 0x440
   __DATA_CONST.__auth_ptr: 0x10

   - /usr/lib/libobjc.A.dylib
   Functions: 499
   Symbols:   349
-  CStrings:  2409
+  CStrings:  2414
 
Functions:
~ sub_33a40 : 68 -> 560
CStrings:
+ "%lld %d AVE %s: %s AVC size overflow %d %d %d %d %lld"
+ "%lld %d AVE %s: %s AVC size overflow %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s HEVC size overflow %d %d %d %d %lld"
+ "%lld %d AVE %s: %s HEVC size overflow %d %d %d %d %lld\n"
+ "20:46:48"
+ "803.73.3"
+ "AVE_CalcBufSizeOfMBInputCtrl"
+ "Jul 21 2026"
- "20:43:04"
- "803.73.1"
- "Apr 29 2026"
```
