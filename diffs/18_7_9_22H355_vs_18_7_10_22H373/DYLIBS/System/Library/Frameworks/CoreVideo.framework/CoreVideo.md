## CoreVideo

> `/System/Library/Frameworks/CoreVideo.framework/CoreVideo`

```diff

-692.1.0.0.0
-  __TEXT.__text: 0x39290
+692.1.101.1.0
+  __TEXT.__text: 0x39468
   __TEXT.__auth_stubs: 0xef0
-  __TEXT.__cstring: 0x7d2b
+  __TEXT.__cstring: 0x7e89
   __TEXT.__objc_databytes: 0x493
   __TEXT.__const: 0xfc3
   __TEXT.__oslogstring: 0x29b

   - /usr/lib/libobjc.A.dylib
   Functions: 1379
   Symbols:   3217
-  CStrings:  877
+  CStrings:  879
 
Functions:
~ _CVPixelBufferCreateWithIOSurface : 664 -> 672
~ _checkIOOrEXSurfaceAndCreatePixelBufferBacking : 2784 -> 3248
CStrings:
+ "checkIOOrEXSurfaceAndCreatePixelBufferBacking returning err %d because planeHeight[planeIndex %u] %u is not equal to %u required by image height %u and verticalSubsampling %u"
+ "checkIOOrEXSurfaceAndCreatePixelBufferBacking returning err %d because planeWidth[planeIndex %u] %u is not equal to %u required by image width %u and horizontalSubsampling %u"
```
