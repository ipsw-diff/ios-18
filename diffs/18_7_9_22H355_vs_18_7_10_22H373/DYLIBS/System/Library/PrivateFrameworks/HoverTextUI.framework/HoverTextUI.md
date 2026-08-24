## HoverTextUI

> `/System/Library/PrivateFrameworks/HoverTextUI.framework/HoverTextUI`

```diff

-3148.15.36.0.0
-  __TEXT.__text: 0x54da0
-  __TEXT.__auth_stubs: 0x1fe0
+3148.15.37.0.0
+  __TEXT.__text: 0x57c80
+  __TEXT.__auth_stubs: 0x2000
   __TEXT.__objc_methlist: 0x404
-  __TEXT.__const: 0x2fe0
-  __TEXT.__cstring: 0x16a9
-  __TEXT.__oslogstring: 0xec9
+  __TEXT.__const: 0x3030
+  __TEXT.__cstring: 0x16b9
+  __TEXT.__oslogstring: 0x1219
   __TEXT.__swift5_typeref: 0x2dc4
   __TEXT.__constg_swiftt: 0x199c
-  __TEXT.__swift5_reflstr: 0x1302
-  __TEXT.__swift5_fieldmd: 0xdc8
+  __TEXT.__swift5_reflstr: 0x1322
+  __TEXT.__swift5_fieldmd: 0xdd4
   __TEXT.__swift5_builtin: 0x140
   __TEXT.__swift5_assocty: 0x288
-  __TEXT.__swift5_capture: 0x618
+  __TEXT.__swift5_capture: 0x65c
   __TEXT.__swift5_proto: 0xe4
   __TEXT.__swift5_types: 0xc4
   __TEXT.__swift5_mpenum: 0x28
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__swift_as_entry: 0x70
-  __TEXT.__swift_as_ret: 0x34
-  __TEXT.__unwind_info: 0x1140
-  __TEXT.__eh_frame: 0x1408
+  __TEXT.__swift_as_entry: 0x84
+  __TEXT.__swift_as_ret: 0x54
+  __TEXT.__unwind_info: 0x1208
+  __TEXT.__eh_frame: 0x1660
   __TEXT.__objc_classname: 0x75
-  __TEXT.__objc_methname: 0x15df
+  __TEXT.__objc_methname: 0x1605
   __TEXT.__objc_methtype: 0x3f1
   __TEXT.__objc_stubs: 0x560
-  __DATA_CONST.__got: 0x608
+  __DATA_CONST.__got: 0x618
   __DATA_CONST.__const: 0x110
   __DATA_CONST.__objc_classlist: 0x50
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x710
+  __DATA_CONST.__objc_selrefs: 0x720
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x10
-  __AUTH_CONST.__auth_got: 0xff8
-  __AUTH_CONST.__const: 0x2340
+  __AUTH_CONST.__auth_got: 0x1008
+  __AUTH_CONST.__const: 0x23e0
   __AUTH_CONST.__cfstring: 0x4c0
-  __AUTH_CONST.__objc_const: 0x1790
+  __AUTH_CONST.__objc_const: 0x17b0
   __AUTH.__objc_data: 0x2d0
-  __AUTH.__data: 0x13b8
+  __AUTH.__data: 0x13a8
   __DATA.__objc_ivar: 0x1c
-  __DATA.__data: 0xff0
+  __DATA.__data: 0x1000
   __DATA.__objc_stublist: 0x8
   __DATA.__bss: 0x1e70
   __DATA.__common: 0x60
   __DATA_DIRTY.__objc_data: 0x488
-  __DATA_DIRTY.__data: 0x178
+  __DATA_DIRTY.__data: 0x188
   __DATA_DIRTY.__common: 0x28
   - /System/Library/Frameworks/Combine.framework/Combine
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1832
-  Symbols:   946
-  CStrings:  576
+  Functions: 1875
+  Symbols:   951
+  CStrings:  591
 
Symbols:
+ _AXkMobileKeyBagLockStatusNotificationID
+ _CFNotificationCenterRemoveEveryObserver
+ _OBJC_CLASS_$_AXSpringBoardServer
+ _kAXSContinuityDisplayStateChangedNotification
+ _objectdestroy.98Tm
CStrings:
+ "Continuity display state changed. isContinuitySessionActive=%{bool}d"
+ "Continuity session active. Removing Hover Typing from view hierarchy."
+ "Continuity session ended and device unlocked. Re-attaching Hover Typing to view hierarchy."
+ "Continuity session ended but device still locked. Will reattach on unlock."
+ "Device lock status changed. AXDeviceIsUnlocked=%{bool}d"
+ "Device locked. Removing Hover Typing from view hierarchy."
+ "Device unlocked. Re-attaching Hover Typing to view hierarchy."
+ "Failed to reattach Hover Typing after lock: %s"
+ "Initial state: isContinuitySessionActive=%{bool}d, isLocked=%{bool}d"
+ "Re-attaching Hover Typing VCs to display manager."
+ "Starting monitor for device lock status (Hover Typing)."
+ "Stopping monitor for device lock status (Hover Typing)."
+ "isContinuitySessionActive"
+ "isDetachedForLock"
+ "windowScene"
```
