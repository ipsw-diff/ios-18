## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2600.140.3.700.1
-  __TEXT.__text: 0x73054
+2600.140.3.700.4
+  __TEXT.__text: 0x730e8
   __TEXT.__auth_stubs: 0x1270
   __TEXT.__const: 0x1fb
   __TEXT.__cstring: 0x69de
-  __TEXT.__oslogstring: 0xfa68
+  __TEXT.__oslogstring: 0xfacb
   __TEXT.__objc_classname: 0x1
   __TEXT.__unwind_info: 0x4f0
   __TEXT.__eh_frame: 0x74

   - /usr/lib/libmrc.dylib
   Functions: 395
   Symbols:   953
-  CStrings:  2099
+  CStrings:  2100
 
Functions:
~ _dns_proxy_input_for_server : 10468 -> 10616
CStrings:
+ "%{public}s: dso_message_received: fatal: %s: remaining message too short for TLV + length: %ld %ld"
+ "23:37:43"
+ "Apr 27 2026"
- "22:58:03"
- "Mar  4 2026"
```
