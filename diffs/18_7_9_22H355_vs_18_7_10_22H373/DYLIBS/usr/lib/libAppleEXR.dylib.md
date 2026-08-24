## libAppleEXR.dylib

> `/usr/lib/libAppleEXR.dylib`

```diff

-3.1.20.1.0
-  __TEXT.__text: 0x9aaa0
+3.1.20.2.0
+  __TEXT.__text: 0x9ac48
   __TEXT.__auth_stubs: 0x460
   __TEXT.__objc_methlist: 0x254
   __TEXT.__const: 0x210bc
   __TEXT.__gcc_except_tab: 0x594
-  __TEXT.__cstring: 0x41c1
+  __TEXT.__cstring: 0x42c0
   __TEXT.__oslogstring: 0x3
   __TEXT.__unwind_info: 0x918
   __TEXT.__eh_frame: 0xf8

   - /usr/lib/libz.1.dylib
   Functions: 735
   Symbols:   968
-  CStrings:  504
+  CStrings:  506
 
Functions:
~ __ZNK11TileDecoder23Interleave_UncompressedEPKvmRK8TileInfojjPvml : 612 -> 644
~ __Z10YCCAtoRGBAIDhLj1EEvPKT_lS2_lPS0_ldRK9YccMatrixjjj : 572 -> 616
~ __Z10YCCAtoRGBAIDhLj2EEvPKT_lS2_lPS0_ldRK9YccMatrixjjj : 620 -> 664
~ __Z10YCCAtoRGBAIfLj1EEvPKT_lS2_lPS0_ldRK9YccMatrixjjj : 996 -> 1040
~ __Z10YCCAtoRGBAIfLj2EEvPKT_lS2_lPS0_ldRK9YccMatrixjjj : 1044 -> 1088
~ __Z9YCCtoRGBAIDhLj1EEvPKT_lS2_lPS0_ldRK9YccMatrixjjj : 584 -> 636
~ __Z9YCCtoRGBAIDhLj2EEvPKT_lS2_lPS0_ldRK9YccMatrixjjj : 588 -> 640
~ __Z9YCCtoRGBAIfLj1EEvPKT_lS2_lPS0_ldRK9YccMatrixjjj : 816 -> 872
~ __Z9YCCtoRGBAIfLj2EEvPKT_lS2_lPS0_ldRK9YccMatrixjjj : 856 -> 912
CStrings:
+ "YCCAtoRGBA: header runLength=%u exceeds destination row capacity (%lu pixels for %lu rowBytes); clamping to prevent OOB write.\n"
+ "YCCtoRGBA: header runLength=%u exceeds destination row capacity (%lu pixels for %lu rowBytes); clamping to prevent OOB write.\n"
```
