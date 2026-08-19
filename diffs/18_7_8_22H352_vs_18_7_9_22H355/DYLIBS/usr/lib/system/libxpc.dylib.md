## libxpc.dylib

> `/usr/lib/system/libxpc.dylib`

```diff

-2894.140.12.0.0
-  __TEXT.__text: 0x3a5e4
+2894.140.12.703.2
+  __TEXT.__text: 0x3a6b0
   __TEXT.__auth_stubs: 0x10f0
   __TEXT.__objc_methlist: 0x32c
   __TEXT.__const: 0x620
-  __TEXT.__cstring: 0x732c
+  __TEXT.__cstring: 0x7392
   __TEXT.__oslogstring: 0x1759
   __TEXT.__dof_libxpc: 0xa5d
-  __TEXT.__unwind_info: 0x10a0
+  __TEXT.__unwind_info: 0x10b8
   __TEXT.__objc_classname: 0x217
   __TEXT.__objc_methname: 0x1e2
   __TEXT.__objc_methtype: 0xb5

   - /usr/lib/system/libsystem_sandbox.dylib
   - /usr/lib/system/libsystem_trace.dylib
   - /usr/lib/system/libunwind.dylib
-  Functions: 1713
+  Functions: 1714
   Symbols:   2462
-  CStrings:  1213
+  CStrings:  1218
 
Functions:
~ __xpc_connection_copy_attrs : 392 -> 472
+ __xpc_connection_copy_attrs.cold.1
CStrings:
+ "Could not get attrs using %s for connection %s, pid %d: %d: %s"
+ "bssendp"
+ "mach port"
+ "pid domain"
+ "token.pid"
```
