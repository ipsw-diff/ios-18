## com.apple.iokit.IOGPUFamily

> `com.apple.iokit.IOGPUFamily`

```diff

-104.6.3.0.0
-  __TEXT.__cstring: 0x5090
-  __TEXT.__os_log: 0x39bc
+104.6.4.0.0
+  __TEXT.__cstring: 0x50d5
+  __TEXT.__os_log: 0x3a06
   __TEXT.__const: 0x7c
-  __TEXT_EXEC.__text: 0x3908c
+  __TEXT_EXEC.__text: 0x39290
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x410
   __DATA.__common: 0x778

   __DATA_CONST.__kalloc_type: 0x1000
   __DATA_CONST.__kalloc_var: 0xf00
   __DATA_CONST.__assert: 0x78
-  Functions: 1736
+  Functions: 1741
   Symbols:   0
-  CStrings:  741
+  CStrings:  745
 
CStrings:
+ "%s: resource does not own its backing (resType=0x%x child=%u device_cache=%s)\n"
+ "%s: resource does not own its backing (resType=0x%x)\n"
+ "IOGPUSysMemory *IOGPUResource::owns_replaceable_backing() const"
+ "IOReturn IOGPUSysMemory::replace_backing_bytes_locked(task_t, mach_vm_address_t, uint64_t)"
+ "IOReturn IOGPUSysMemory::replace_backing_ranges_locked(task_t, IOAddressRange *, uint32_t, bool)"
+ "NO"
+ "YES"
- "Attempting to detach memory for invalid resource type: %u\n"
- "virtual IOReturn IOGPUSysMemory::replace_backing_bytes(task_t, mach_vm_address_t, uint64_t)"
- "virtual IOReturn IOGPUSysMemory::replace_backing_ranges(task_t, IOAddressRange *, uint32_t, bool)"
```
