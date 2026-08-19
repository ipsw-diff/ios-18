## launchd

> `/sbin/launchd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__dof_launchd`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`
- `__DATA.__os_assumes_log`

```diff

-2894.140.12.0.0
-  __TEXT.__text: 0x5168c
+2894.140.12.703.2
+  __TEXT.__text: 0x51788
   __TEXT.__auth_stubs: 0x2110
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x1f4
   __TEXT.__const: 0x2f0
-  __TEXT.__cstring: 0x147d3
+  __TEXT.__cstring: 0x1483c
   __TEXT.__launchd: 0x1
   __TEXT.__objc_methname: 0x8
   __TEXT.__objc_classname: 0x1ba

   - /usr/lib/libsandbox.1.dylib
   Functions: 1639
   Symbols:   582
-  CStrings:  2618
+  CStrings:  2621
 
Functions:
~ sub_10002885c : 196 -> 448
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Mon Apr 27 22:58:27 PDT 2026; root:libxpc_executables-2894.140.12.703.2~2/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Mon Apr 27 22:58:27 PDT 2026; root:libxpc_executables-2894.140.12.703.2~2/launchd/RELEASE_ARM64E"
+ "not allowed to copy attrs for service"
+ "pid %d not allowed to get properties for service"
+ "xpc-fault"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sat Aug  9 01:29:16 PDT 2025; root:libxpc_executables-2894.140.12~128/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Sat Aug  9 01:29:16 PDT 2025; root:libxpc_executables-2894.140.12~128/launchd/RELEASE_ARM64E"
```
