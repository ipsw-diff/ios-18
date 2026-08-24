## IMDaemonCore

> `/System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore`

```diff

-1402.700.53.2.29
-  __TEXT.__text: 0x293d18
+1402.700.53.2.33
+  __TEXT.__text: 0x294260
   __TEXT.__auth_stubs: 0x44f0
   __TEXT.__objc_methlist: 0x16ab4
-  __TEXT.__const: 0x3608
+  __TEXT.__const: 0x3618
   __TEXT.__cstring: 0x129e1
-  __TEXT.__gcc_except_tab: 0x27224
-  __TEXT.__oslogstring: 0x457b7
+  __TEXT.__gcc_except_tab: 0x272c0
+  __TEXT.__oslogstring: 0x45947
   __TEXT.__ustring: 0x4d4
   __TEXT.__dlopen_cstrs: 0x128
   __TEXT.__constg_swiftt: 0x10f4

   __TEXT.__swift_as_ret: 0xf4
   __TEXT.__swift5_protos: 0x18
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0xadd8
+  __TEXT.__unwind_info: 0xade0
   __TEXT.__eh_frame: 0x240c
   __TEXT.__objc_classname: 0x2e0a
-  __TEXT.__objc_methname: 0x45ae1
+  __TEXT.__objc_methname: 0x45b0a
   __TEXT.__objc_methtype: 0x9386
   __TEXT.__objc_stubs: 0x2c8a0
   __DATA_CONST.__got: 0x2b60

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 10086
   Symbols:   2714
-  CStrings:  17513
+  CStrings:  17517
 
Functions:
~ sub_1d963e368 -> sub_1d9ffe368 : 1644 -> 2008
~ sub_1d9652448 -> sub_1da0125b4 : 2560 -> 2616
~ sub_1d970d814 -> sub_1da0cd9b8 : 292 -> 348
~ sub_1d970d938 -> sub_1da0cdb14 : 140 -> 612
~ sub_1d977307c -> sub_1da133430 : 884 -> 956
~ sub_1d97d51d8 -> sub_1da1955d4 : 1620 -> 1952
CStrings:
+ "Adding message GUID to readReceiptsForMissingMessage cache: %@ sender: %@ (size: %lu)"
+ "Dropping cached read receipt for missing message %@: receipt not from me for a message not from me"
+ "Dropping cached read receipt for missing message %@: receipt sender %@ is not the recipient %@"
+ "Rejecting c=112 (delivered-quietly) for GUID=%@ (msg.isFromMe=%{BOOL}d, sender=%{private}@, handle=%{private}@)"
+ "Rejecting c=113 (notify-recipient) for GUID=%@ (sender=%{private}@, handle=%{private}@)"
+ "addMissingMessageReadReceipt:sender:"
+ "popReadReceiptForMissingGUID:messageIsFromMe:account:recipient:"
- "Adding message GUID to readReceiptsForMissingMessage cache: %@ (size: %lu)"
- "addMissingMessageReadReceipt:"
- "popReadReceiptForMissingGUID:"
```
