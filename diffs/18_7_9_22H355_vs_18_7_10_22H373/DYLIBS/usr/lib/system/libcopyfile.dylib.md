## libcopyfile.dylib

> `/usr/lib/system/libcopyfile.dylib`

```diff

-224.0.0.0.0
-  __TEXT.__text: 0x7578
-  __TEXT.__auth_stubs: 0x660
+224.0.0.701.1
+  __TEXT.__text: 0x783c
+  __TEXT.__auth_stubs: 0x630
   __TEXT.__const: 0x1c8
-  __TEXT.__cstring: 0x1a10
-  __TEXT.__unwind_info: 0xe8
+  __TEXT.__cstring: 0x1b37
+  __TEXT.__unwind_info: 0xf0
   __DATA_CONST.__got: 0x28
   __DATA_CONST.__const: 0x3b0
-  __AUTH_CONST.__auth_got: 0x330
+  __AUTH_CONST.__auth_got: 0x318
   __AUTH_CONST.__const: 0xe0
   __DATA_DIRTY.__bss: 0x10
   - /usr/lib/system/libcompiler_rt.dylib

   - /usr/lib/system/libsystem_kernel.dylib
   - /usr/lib/system/libsystem_malloc.dylib
   - /usr/lib/system/libxpc.dylib
-  Functions: 37
-  Symbols:   152
-  CStrings:  191
+  Functions: 39
+  Symbols:   151
+  CStrings:  197
 
Symbols:
+ _copyfile_set_dst_permissions
+ _copyfile_validate_dst
- _chmod
- _chmodx_np
- _chown
CStrings:
+ "cannot open destination for permission elevation: %s: %m"
+ "destination file %s changed behind our feet: %m"
+ "fchmodx_np on destination readonly fd: %m"
+ "fstat failed on destination readonly fd: %s: %m"
+ "fstat failed on readonly fd during validation: %m"
+ "fstat failed on writable fd during validation: %m"
```
