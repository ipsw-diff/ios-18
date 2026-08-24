## sharingd

> `/usr/libexec/sharingd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methtype`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-2060.80.31.2.7
-  __TEXT.__text: 0x6ae35c
+2060.80.31.2.11
+  __TEXT.__text: 0x6ae6f0
   __TEXT.__auth_stubs: 0x9470
-  __TEXT.__objc_stubs: 0x34a00
-  __TEXT.__objc_methlist: 0x1f7dc
-  __TEXT.__cstring: 0x47543
-  __TEXT.__objc_methname: 0x49e58
+  __TEXT.__objc_stubs: 0x34a20
+  __TEXT.__objc_methlist: 0x1f7ec
+  __TEXT.__cstring: 0x475b3
+  __TEXT.__objc_methname: 0x49e7c
   __TEXT.__objc_classname: 0x2dd6
   __TEXT.__objc_methtype: 0xa393
-  __TEXT.__const: 0x16b30
+  __TEXT.__const: 0x16be0
   __TEXT.__gcc_except_tab: 0x6b58
-  __TEXT.__oslogstring: 0x3b499
+  __TEXT.__oslogstring: 0x3b519
   __TEXT.__ustring: 0x94
   __TEXT.__dlopen_cstrs: 0x31b
-  __TEXT.__swift5_typeref: 0x9920
-  __TEXT.__swift5_fieldmd: 0x7f64
-  __TEXT.__constg_swiftt: 0xa704
+  __TEXT.__swift5_typeref: 0x992e
+  __TEXT.__swift5_fieldmd: 0x7f8c
+  __TEXT.__constg_swiftt: 0xa720
   __TEXT.__swift5_builtin: 0x348
-  __TEXT.__swift5_reflstr: 0x6ac7
+  __TEXT.__swift5_reflstr: 0x6ad7
   __TEXT.__swift5_assocty: 0x13c0
   __TEXT.__swift5_protos: 0x1f8
-  __TEXT.__swift5_proto: 0x12e4
-  __TEXT.__swift5_types: 0x848
+  __TEXT.__swift5_proto: 0x12f0
+  __TEXT.__swift5_types: 0x84c
   __TEXT.__swift_as_entry: 0xcd8
   __TEXT.__swift_as_ret: 0xd44
   __TEXT.__swift5_capture: 0x3f84

   __TEXT.__eh_frame: 0x25370
   __DATA_CONST.__auth_got: 0x4a48
   __DATA_CONST.__got: 0x3300
-  __DATA_CONST.__auth_ptr: 0x2390
-  __DATA_CONST.__const: 0x1d658
-  __DATA_CONST.__cfstring: 0x19920
+  __DATA_CONST.__auth_ptr: 0x2398
+  __DATA_CONST.__const: 0x1d6e8
+  __DATA_CONST.__cfstring: 0x199a0
   __DATA_CONST.__objc_classlist: 0xee0
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x6d8

   __DATA_CONST.__objc_arrayobj: 0x6f0
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA.__objc_const: 0x3b038
-  __DATA.__objc_selrefs: 0x11060
+  __DATA.__objc_selrefs: 0x11068
   __DATA.__objc_ivar: 0x2ad8
   __DATA.__objc_data: 0xae38
-  __DATA.__data: 0x18150
-  __DATA.__bss: 0x14c98
+  __DATA.__data: 0x18170
+  __DATA.__bss: 0x14e18
   __DATA.__common: 0xaa8
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/Accounts.framework/Accounts

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 27017
+  Functions: 27022
   Symbols:   4294
-  CStrings:  27558
+  CStrings:  27564
 
CStrings:
+ "Unhandled AirDrop request path: %s"
+ "com.apple.private.sharing.activity-advertiser"
+ "com.apple.private.tcc.allow"
+ "com.apple.security.personal-information.addressbook"
+ "kTCCServiceAddressBook"
+ "process %d tried to connect to the handoff advertising server, but it was not entitled!"
+ "sd_connectionHasContactsEntitlement"
- "DaemoniOSLibrary/Network+SFAirDropMessage.swift"
```
