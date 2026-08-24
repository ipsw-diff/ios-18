## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/ImageIO`

```diff

-2661.8.3.0.3
-  __TEXT.__text: 0x469898
-  __TEXT.__auth_stubs: 0x41d0
+2661.8.3.0.7
+  __TEXT.__text: 0x469da8
+  __TEXT.__auth_stubs: 0x41e0
   __TEXT.__objc_methlist: 0xb58
   __TEXT.__const: 0xb8a28
-  __TEXT.__gcc_except_tab: 0x1ff74
-  __TEXT.__cstring: 0x7d29d
+  __TEXT.__gcc_except_tab: 0x1ff9c
+  __TEXT.__cstring: 0x7d422
   __TEXT.__oslogstring: 0x17
   __TEXT.__ustring: 0x30
-  __TEXT.__unwind_info: 0xd960
+  __TEXT.__unwind_info: 0xd978
   __TEXT.__eh_frame: 0x510
   __TEXT.__objc_classname: 0xce
   __TEXT.__objc_methname: 0x2a12

   __DATA_CONST.__objc_selrefs: 0xa48
   __DATA_CONST.__objc_superrefs: 0x30
   __DATA_CONST.__objc_arraydata: 0x20
-  __AUTH_CONST.__auth_got: 0x2100
+  __AUTH_CONST.__auth_got: 0x2108
   __AUTH_CONST.__const: 0x3cdf8
   __AUTH_CONST.__cfstring: 0xde80
   __AUTH_CONST.__objc_const: 0xe50

   - /usr/lib/libz.1.dylib
   Functions: 13928
   Symbols:   18062
-  CStrings:  12831
+  CStrings:  12836
 
Symbols:
+ _CGImageBlockSetGetColorSpace
+ __ZN19HEIFStereoAggressor13writeToStreamEP15__CFWriteStream
- _ERROR_ImageIO_DataBufferIsNotBigEnough
- __ZN10IIOScanner14validateBufferEPKc
CStrings:
+ "*** Error: auxiliary data buffer too small (have %ld, need %zu) for %zux%zu rb=%zu\n"
+ "*** NOTE: _tiff._tiffRowsPerStrip: %u   _tiff._tiffHeight: %u\n"
+ "Error in TIFFRGBAImageGet: row offset %d exceeds image height %d"
+ "Error in gtStripContig: column offset %d exceeds image width %d"
+ "Error in gtStripSeparate: column offset %d exceeds image width %d"
+ "Error in gtTileContig: column offset %d exceeds image width %d"
+ "Error in gtTileSeparate: column offset %d exceeds image width %d"
+ "stride %lld is not a multiple of sample count, %lld, data truncated."
- "*** NOTE: _tiff._tiffRowsPerStrip: %d   _tiff._tiffHeight: %d\n"
- "Checking ATX buffer"
- "stride %d is not a multiple of sample count, %lld, data truncated."
```
