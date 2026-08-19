## EventKitUI

> `/System/Library/Frameworks/EventKitUI.framework/EventKitUI`

```diff

-1490.6.1.0.0
-  __TEXT.__text: 0x1cbbd0
-  __TEXT.__auth_stubs: 0x2230
+1490.6.1.2.0
+  __TEXT.__text: 0x1cbc1c
+  __TEXT.__auth_stubs: 0x2240
   __TEXT.__objc_methlist: 0x1df74
   __TEXT.__const: 0x2544
   __TEXT.__cstring: 0xda71

   __TEXT.__unwind_info: 0x7368
   __TEXT.__eh_frame: 0x618
   __TEXT.__objc_classname: 0x4185
-  __TEXT.__objc_methname: 0x439ef
+  __TEXT.__objc_methname: 0x43a00
   __TEXT.__objc_methtype: 0xbcac
   __TEXT.__objc_stubs: 0x31180
   __DATA_CONST.__got: 0x1948

   __DATA_CONST.__objc_protorefs: 0xd8
   __DATA_CONST.__objc_superrefs: 0x8a0
   __DATA_CONST.__objc_arraydata: 0x260
-  __AUTH_CONST.__auth_got: 0x1128
+  __AUTH_CONST.__auth_got: 0x1130
   __AUTH_CONST.__const: 0x2740
   __AUTH_CONST.__cfstring: 0xb200
-  __AUTH_CONST.__objc_const: 0x2f380
+  __AUTH_CONST.__objc_const: 0x2f3a0
   __AUTH_CONST.__objc_intobj: 0x600
   __AUTH_CONST.__objc_arrayobj: 0x228
   __AUTH_CONST.__objc_doubleobj: 0x70

   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH.__objc_data: 0x79e8
   __AUTH.__data: 0xbe0
-  __DATA.__objc_ivar: 0x23e8
+  __DATA.__objc_ivar: 0x23ec
   __DATA.__data: 0x4b10
   __DATA.__bss: 0x1620
   __DATA.__common: 0x218

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 11433
-  Symbols:   23754
-  CStrings:  14527
+  Symbols:   23756
+  CStrings:  14528
 
Symbols:
+ _CUIKTruncateStringForAvailableSpace
+ _OBJC_IVAR_$_EKEventDetailTextCell._forceTruncation
Functions:
~ -[EKUIListViewAllDayEventCell updateWithEvent:dimmed:] : 840 -> 844
~ -[EKUIListViewTimedEventCell updateWithEvent:isMultiday:occurrenceStartDate:dimmed:] : 1884 -> 1888
~ -[EKEventDetailTextCell update] : 444 -> 492
~ -[EKEventDetailTextCell _sizeForTextViewGivenWidth:outTruncatingText:] : 468 -> 488
CStrings:
+ "_forceTruncation"
```
