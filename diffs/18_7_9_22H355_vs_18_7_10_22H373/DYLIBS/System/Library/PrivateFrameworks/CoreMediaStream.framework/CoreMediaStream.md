## CoreMediaStream

> `/System/Library/PrivateFrameworks/CoreMediaStream.framework/CoreMediaStream`

```diff

-770.0.173.0.0
-  __TEXT.__text: 0xc0a2c
+770.0.174.0.0
+  __TEXT.__text: 0xc0a84
   __TEXT.__auth_stubs: 0xfa0
   __TEXT.__objc_methlist: 0x74c0
   __TEXT.__const: 0x1db
-  __TEXT.__cstring: 0x9f79
+  __TEXT.__cstring: 0x9f7b
   __TEXT.__dlopen_cstrs: 0x47
   __TEXT.__gcc_except_tab: 0x2bcc
-  __TEXT.__oslogstring: 0xe8dd
+  __TEXT.__oslogstring: 0xe8df
   __TEXT.__unwind_info: 0x28b8
   __TEXT.__objc_classname: 0x813
-  __TEXT.__objc_methname: 0x12977
+  __TEXT.__objc_methname: 0x129aa
   __TEXT.__objc_methtype: 0x4265
-  __TEXT.__objc_stubs: 0xc860
+  __TEXT.__objc_stubs: 0xc8a0
   __DATA_CONST.__got: 0x4c0
   __DATA_CONST.__const: 0x2278
   __DATA_CONST.__objc_classlist: 0x200
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0xe0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3ea0
+  __DATA_CONST.__objc_selrefs: 0x3eb0
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x1c0
   __AUTH_CONST.__auth_got: 0x7e0
   __AUTH_CONST.__const: 0x890
-  __AUTH_CONST.__cfstring: 0x8040
+  __AUTH_CONST.__cfstring: 0x8060
   __AUTH_CONST.__objc_const: 0x8728
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH.__objc_data: 0x50

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   Functions: 3278
-  Symbols:   6853
-  CStrings:  5132
+  Symbols:   6855
+  CStrings:  5134
 
Symbols:
+ -[MSAlbumSharingDaemon updateOwnerReputationScoreForAlbum:withAddress:]
+ _objc_msgSend$containsString:
+ _objc_msgSend$handleWithPhoneNumber:
+ _objc_msgSend$updateOwnerReputationScoreForAlbum:withAddress:
- -[MSAlbumSharingDaemon updateOwnerReputationScoreForAlbum:]
- _objc_msgSend$updateOwnerReputationScoreForAlbum:
Functions:
~ -[MSAlbumSharingDaemon updateOwnerReputationScoreForAlbum:] -> -[MSAlbumSharingDaemon updateOwnerReputationScoreForAlbum:withAddress:] : 456 -> 488
~ -[MSAlbumSharingDaemon addAlbum:] : 264 -> 292
~ -[MSASServerSideModel dbQueueSetAlbum:info:] : 1236 -> 1264
CStrings:
+ "%{public}@: Unexpected nil album owner address"
+ "containsString:"
+ "handleWithPhoneNumber:"
+ "updateOwnerReputationScoreForAlbum:withAddress:"
- "%{public}@: Unexpected nil album owner email"
- "updateOwnerReputationScoreForAlbum:"
```
