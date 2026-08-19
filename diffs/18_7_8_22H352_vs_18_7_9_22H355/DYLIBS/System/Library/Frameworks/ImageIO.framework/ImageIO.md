## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/ImageIO`

```diff

-2661.8.3.0.0
-  __TEXT.__text: 0x469050
+2661.8.3.0.3
+  __TEXT.__text: 0x469898
   __TEXT.__auth_stubs: 0x41d0
   __TEXT.__objc_methlist: 0xb58
   __TEXT.__const: 0xb8a28
-  __TEXT.__gcc_except_tab: 0x1ff34
-  __TEXT.__cstring: 0x7d198
+  __TEXT.__gcc_except_tab: 0x1ff74
+  __TEXT.__cstring: 0x7d29d
   __TEXT.__oslogstring: 0x17
   __TEXT.__ustring: 0x30
-  __TEXT.__unwind_info: 0xd928
+  __TEXT.__unwind_info: 0xd960
   __TEXT.__eh_frame: 0x510
   __TEXT.__objc_classname: 0xce
   __TEXT.__objc_methname: 0x2a12

   - /usr/lib/libexpat.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 13917
-  Symbols:   18055
-  CStrings:  12824
+  Functions: 13928
+  Symbols:   18062
+  CStrings:  12831
 
Symbols:
+ __ZL21releaseGlobalWebPInfoPv
+ __ZN14GlobalWebPInfo14setFrameBufferEPhmjjj
+ __ZN14GlobalWebPInfo15copyFrameBufferEPPhPmPj
+ __ZN14GlobalWebPInfo16clearFrameBufferEv
+ __ZN14GlobalWebPInfo19hasValidFrameBufferEj
+ __ZN14GlobalWebPInfoD2Ev
+ __ZN14WebPReadPlugin24copyDecodedFrameToBufferEPhS0_jjji
+ __ZN14WebPReadPlugin27decodeAnimatedWebPOptimizedEP8WebPDataPhm
- __ZN14WebPReadPlugin18decodeAnimatedWebPEP8WebPDataPhm
CStrings:
+ " countS = %ld   count = %ld   _length = %ld   offset = %ld \n"
+ "*** ERROR: decodeAnimatedWebPOptimized failed\n"
+ "*** ERROR: failed to create temp file (err = %d '%s')\n"
+ "*** ERROR: invalid canvas dimensions %dx%d\n"
+ "*** ERROR: invalid canvas size %dx%d\n"
+ "*** ERROR: setFrameBuffer - bailing out\n"
+ "*** too many bytes to allocate\n"
+ "decodeAnimatedWebPOptimized"
+ "setFrameBuffer"
- " inCount = %ld   count = %ld   _length = %ld   offset = %ld \n"
- "*** ERROR: decodeAnimatedWebP failed\n"
```
