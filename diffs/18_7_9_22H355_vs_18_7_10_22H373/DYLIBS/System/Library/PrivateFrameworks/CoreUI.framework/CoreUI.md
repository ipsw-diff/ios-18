## CoreUI

> `/System/Library/PrivateFrameworks/CoreUI.framework/CoreUI`

```diff

-918.3.2.0.0
-  __TEXT.__text: 0xa5074
+918.3.3.0.0
+  __TEXT.__text: 0xa515c
   __TEXT.__auth_stubs: 0x2630
   __TEXT.__objc_methlist: 0x8918
   __TEXT.__const: 0x49f8
-  __TEXT.__cstring: 0x23c8d
+  __TEXT.__cstring: 0x23d9d
   __TEXT.__gcc_except_tab: 0x1424
   __TEXT.__oslogstring: 0x52
   __TEXT.__swift5_typeref: 0x72

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 4364
   Symbols:   8980
-  CStrings:  9086
+  CStrings:  9089
 
Functions:
~ -[CUIThemeRendition _initWithCSIData:forKey:version:] : 296 -> 360
~ -[CUIThemeRendition initWithCSIData:forKey:version:] : 208 -> 224
~ -[_CSIRenditionBlockData expandCSIBitmapData:fromSlice:makeReadOnly:] : 1624 -> 1628
~ _CUIExpandATECompressedDataIntoBuffer : 1056 -> 1204
CStrings:
+ "CoreUI: %s embedded image dimensions (%u x %u) exceed allocated buffer (%u rows)"
+ "CoreUI: %s source block data (%zu bytes available) too small for image dimensions (%zu bytes required)"
+ "CoreUI: CSI data has invalid chainsize (%u) or image count (%u) for key %@"
+ "_Bool CUIExpandATECompressedDataIntoBuffer(const u_int8_t *, _Bool, u_int8_t *, enum CSIPixelFormat, size_t, u_int32_t)"
- "_Bool CUIExpandATECompressedDataIntoBuffer(const u_int8_t *, _Bool, u_int8_t *, enum CSIPixelFormat, size_t)"
```
