## GameCenterFoundation

> `/System/Library/PrivateFrameworks/GameCenterFoundation.framework/GameCenterFoundation`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-819.4.47.0.0
-  __TEXT.__text: 0x16cecc
+819.4.47.2.1
+  __TEXT.__text: 0x16cfc0
   __TEXT.__auth_stubs: 0x2750
   __TEXT.__objc_methlist: 0x11c44
   __TEXT.__cstring: 0x19423
   __TEXT.__const: 0x5848
   __TEXT.__gcc_except_tab: 0x13fc
-  __TEXT.__oslogstring: 0xd69b
+  __TEXT.__oslogstring: 0xd6eb
   __TEXT.__ustring: 0x18
   __TEXT.__dlopen_cstrs: 0xba
   __TEXT.__swift5_typeref: 0x1df0

   __TEXT.__unwind_info: 0x6598
   __TEXT.__eh_frame: 0x5940
   __TEXT.__objc_classname: 0x1e60
-  __TEXT.__objc_methname: 0x25e08
+  __TEXT.__objc_methname: 0x25df8
   __TEXT.__objc_methtype: 0x613c
-  __TEXT.__objc_stubs: 0x14b60
+  __TEXT.__objc_stubs: 0x14b40
   __DATA_CONST.__got: 0x1080
   __DATA_CONST.__const: 0x5f80
   __DATA_CONST.__objc_classlist: 0x7f8
   __DATA_CONST.__objc_catlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x228
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8230
+  __DATA_CONST.__objc_selrefs: 0x8228
   __DATA_CONST.__objc_protorefs: 0x128
   __DATA_CONST.__objc_superrefs: 0x4e8
   __DATA_CONST.__objc_arraydata: 0x2a8

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 10669
-  Symbols:   14687
+  Functions: 10670
+  Symbols:   14686
   CStrings:  10461
 
Symbols:
- _objc_msgSend$containsString:
Functions:
~ _GKImageCachePathForSubdirectoryAndFilename : 108 -> 256
~ +[NSData(GKAdditions) _gkLoadRemoteImageDataForUrl:session:subdirectory:filename:queue:imageQueue:handler:] : 1440 -> 1432
+ _GKImageCachePathForSubdirectoryAndFilename.cold.1
~ ___107+[NSData(GKAdditions) _gkLoadRemoteImageDataForUrl:session:subdirectory:filename:queue:imageQueue:handler:]_block_invoke_2.cold.2 : 140 -> 124
CStrings:
+ ".."
+ "Blocked path traversal attempt in image cache filename: %@"
+ "Illegal file cache path for subdirectory: %@, filename: %@"
- "../"
- "Illegal file cache path: %@"
- "containsString:"
```
