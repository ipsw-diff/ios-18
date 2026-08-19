## MultitouchSupport

> `/System/Library/PrivateFrameworks/MultitouchSupport.framework/MultitouchSupport`

```diff

-8140.7.0.0.0
-  __TEXT.__text: 0x1e468
+8140.8.0.0.0
+  __TEXT.__text: 0x1e644
   __TEXT.__auth_stubs: 0xe70
   __TEXT.__objc_methlist: 0x2ec
   __TEXT.__const: 0x2010
   __TEXT.__cstring: 0x16df
-  __TEXT.__oslogstring: 0x10ca
+  __TEXT.__oslogstring: 0x11c2
   __TEXT.__tpad_act_plist: 0xe22d
-  __TEXT.__unwind_info: 0x6d0
+  __TEXT.__unwind_info: 0x6d8
   __TEXT.__objc_classname: 0x49
   __TEXT.__objc_methname: 0x682
   __TEXT.__objc_methtype: 0x591

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 661
-  Symbols:   1037
-  CStrings:  484
+  Functions: 662
+  Symbols:   1038
+  CStrings:  488
 
Symbols:
+ _mtalg_MaxContacts
Functions:
~ _mt_UncompressTouchpadCodecV1Force : 388 -> 792
+ _mtalg_MaxContacts
~ _MTParse_CompactV10BinaryPath : 460 -> 472
~ __Z26MTParse_PrecisePathPayloadPhiP28MTParsedMultitouchFrameRep_tP10__MTDeviceittb : 856 -> 860
~ _MTParse_HostPathAndImage : 388 -> 400
~ _mt_ForwardBinaryContacts : 604 -> 624
CStrings:
+ "Force sensor position(%d) calculation hit a critical error"
+ "Force sensor position(%d) exceeded the force pixel count(%d)"
+ "Raw force sensor position(%d) calculation hit a critical error"
+ "Raw force sensor position(%d) exceeded the force pixel count(%d)"
```
