## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__data`

```diff

-2600.140.3.700.1
-  __TEXT.__text: 0xfe848
+2600.140.3.700.4
+  __TEXT.__text: 0xfe828
   __TEXT.__auth_stubs: 0x2df0
   __TEXT.__objc_stubs: 0x1220
   __TEXT.__objc_methlist: 0x334
Functions:
~ _SameRDataBody : 612 -> 548
~ _CreateNewCacheEntryEx : 2368 -> 2384
~ _mDNSCoreReceiveUpdate : 3160 -> 3176
CStrings:
+ "mDNSResponder-2600.140.3.700.4"
- "mDNSResponder-2600.140.3.700.1"
```
