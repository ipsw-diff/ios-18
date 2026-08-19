## securityd

> `/usr/libexec/securityd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-61439.140.12.704.2
-  __TEXT.__text: 0x235274
+61439.140.12.704.3
+  __TEXT.__text: 0x235534
   __TEXT.__auth_stubs: 0x39b0
-  __TEXT.__objc_stubs: 0x1aea0
+  __TEXT.__objc_stubs: 0x1aec0
   __TEXT.__objc_methlist: 0x14728
   __TEXT.__const: 0x3e5
-  __TEXT.__cstring: 0x1fa0c
-  __TEXT.__oslogstring: 0x2994f
+  __TEXT.__cstring: 0x1faf2
+  __TEXT.__oslogstring: 0x299b1
   __TEXT.__dlopen_cstrs: 0x1c8
   __TEXT.__gcc_except_tab: 0xad8c
   __TEXT.__objc_classname: 0x2289
-  __TEXT.__objc_methname: 0x2a2ae
+  __TEXT.__objc_methname: 0x2a2be
   __TEXT.__objc_methtype: 0x9db0
   __TEXT.__ustring: 0x28
-  __TEXT.__unwind_info: 0x60b0
+  __TEXT.__unwind_info: 0x60b8
   __DATA_CONST.__auth_got: 0x1ce8
   __DATA_CONST.__got: 0x1080
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA_CONST.__const: 0x137f0
-  __DATA_CONST.__cfstring: 0x1a900
+  __DATA_CONST.__const: 0x13818
+  __DATA_CONST.__cfstring: 0x1a960
   __DATA_CONST.__objc_classlist: 0x870
   __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0x210

   __DATA_CONST.__objc_arrayobj: 0x360
   __DATA_CONST.__objc_dictobj: 0x78
   __DATA.__objc_const: 0x21950
-  __DATA.__objc_selrefs: 0x8c18
+  __DATA.__objc_selrefs: 0x8c20
   __DATA.__objc_ivar: 0x1958
   __DATA.__objc_data: 0x5460
   __DATA.__data: 0x1ee8

   - /usr/lib/libz.1.dylib
   Functions: 9147
   Symbols:   1476
-  CStrings:  15040
+  CStrings:  15045
 
Functions:
~ sub_10002d900 : 908 -> 1204
~ sub_10002dd08 -> sub_10002de30 : 368 -> 776
CStrings:
+ "ckkscurrent-oob: CKKS returned a PCS Identity that the client doesn't have an entitlement for: %@"
+ "decryptedRecord"
+ "secItemFetchPCSIdentityByKeyOutOfBand: %@ does not have entitlement %@"
+ "secItemFetchPCSIdentityByKeyOutOfBand: client did not specify an access group: %@"
+ "secItemFetchPCSIdentityByKeyOutOfBand: client is missing access group %@: %@"
```
