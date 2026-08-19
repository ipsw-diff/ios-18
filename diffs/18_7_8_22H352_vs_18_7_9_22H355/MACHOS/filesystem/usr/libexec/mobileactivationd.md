## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1017.142.1.0.0
-  __TEXT.__text: 0x1fe25c
+1017.142.1.700.1
+  __TEXT.__text: 0x1fe28c
   __TEXT.__auth_stubs: 0x10a0
-  __TEXT.__objc_stubs: 0x2f20
-  __TEXT.__objc_methlist: 0x1084
+  __TEXT.__objc_stubs: 0x2f40
+  __TEXT.__objc_methlist: 0x108c
   __TEXT.__const: 0x468c1
-  __TEXT.__cstring: 0xda35
-  __TEXT.__objc_methname: 0x3d4e
+  __TEXT.__cstring: 0xda51
+  __TEXT.__objc_methname: 0x3d65
   __TEXT.__oslogstring: 0xe5a
   __TEXT.__objc_classname: 0x1b4
   __TEXT.__objc_methtype: 0x102a

   __DATA_CONST.__objc_arraydata: 0x468
   __DATA_CONST.__objc_arrayobj: 0x90
   __DATA.__objc_const: 0x1850
-  __DATA.__objc_selrefs: 0xfe0
+  __DATA.__objc_selrefs: 0xfe8
   __DATA.__objc_ivar: 0xf4
   __DATA.__objc_data: 0x320
   __DATA.__data: 0x1210

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/liblockdown.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1389
-  Symbols:   3387
-  CStrings:  2817
+  Functions: 1390
+  Symbols:   3389
+  CStrings:  2818
 
Symbols:
+ -[DeviceType copyDeviceTreeInt:key:]
+ _objc_msgSend$copyDeviceTreeInt:key:
CStrings:
+ "1017.142.1.700.1"
+ "Absinthe/2.0 iOS Device Activator (MobileActivation-1017.142.1.700.1 built on Apr 28 2026 at 23:50:31)"
+ "certificate-production-status"
+ "certificate-security-mode"
+ "copyDeviceTreeInt:key:"
+ "effective-production-status-ap"
+ "effective-security-mode-sep"
+ "iOS Device Activator (MobileActivation-1017.142.1.700.1)"
- "1017.142.1"
- "Absinthe/2.0 iOS Device Activator (MobileActivation-1017.142.1 built on Mar  4 2026 at 22:28:36)"
- "CertificateProductionStatus"
- "CertificateSecurityMode"
- "EffectiveProductionStatusAp"
- "EffectiveSecurityModeSEP"
- "iOS Device Activator (MobileActivation-1017.142.1)"
```
