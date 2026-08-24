## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2600.140.3.700.4
-  __TEXT.__text: 0xfe828
+2600.140.3.700.6
+  __TEXT.__text: 0xfef84
   __TEXT.__auth_stubs: 0x2df0
   __TEXT.__objc_stubs: 0x1220
   __TEXT.__objc_methlist: 0x334
   __TEXT.__const: 0x1130
-  __TEXT.__cstring: 0x16fb6
+  __TEXT.__cstring: 0x16fb2
   __TEXT.__gcc_except_tab: 0x154
   __TEXT.__oslogstring: 0x1dc06
   __TEXT.__objc_classname: 0x5f9
   __TEXT.__objc_methname: 0x106c
   __TEXT.__objc_methtype: 0x52d
-  __TEXT.__unwind_info: 0x1580
+  __TEXT.__unwind_info: 0x1578
   __DATA_CONST.__auth_got: 0x1708
   __DATA_CONST.__got: 0x2c0
   __DATA_CONST.__auth_ptr: 0x70

   - /usr/lib/libnetworkextension.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 1739
-  Symbols:   3789
-  CStrings:  4427
+  Functions: 1738
+  Symbols:   3788
+  CStrings:  4426
 
Symbols:
+ GCC_except_table1168
+ GCC_except_table1175
+ GCC_except_table1305
+ GCC_except_table1499
- GCC_except_table1169
- GCC_except_table1176
- GCC_except_table1306
- GCC_except_table1500
- _ResourceRecordGetRDataBytesPointer
Functions:
~ _mDNS_Register_internal : 5456 -> 5568
~ _GetRDLength : 476 -> 460
~ _request_callback : 43152 -> 42828
~ _putRData : 2540 -> 2484
~ _regrecord_callback : 4076 -> 4228
~ _FoundInstance : 10920 -> 11492
~ _connection_termination : 2876 -> 2944
~ _DNSTypeName : 572 -> 548
~ _GetRRDisplayString_rdb : 2912 -> 2860
- _ResourceRecordGetRDataBytesPointer
~ _SetRData : 4568 -> 4540
~ __handle_regrecord_request_start : 5452 -> 5620
~ _queryrecord_result_reply : 24408 -> 25416
~ _resolve_result_callback : 14104 -> 14588
CStrings:
+ "mDNSResponder-2600.140.3.700.6"
- "TSR"
- "mDNSResponder-2600.140.3.700.4"
```
