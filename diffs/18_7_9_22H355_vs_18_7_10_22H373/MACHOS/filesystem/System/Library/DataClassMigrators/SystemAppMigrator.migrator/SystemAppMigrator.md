## SystemAppMigrator

> `/System/Library/DataClassMigrators/SystemAppMigrator.migrator/SystemAppMigrator`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-1378.100.35.0.0
-  __TEXT.__text: 0xa1a4
+1378.100.35.700.1
+  __TEXT.__text: 0xa198
   __TEXT.__auth_stubs: 0x880
   __TEXT.__objc_stubs: 0x1860
   __TEXT.__objc_methlist: 0x7c4

   __TEXT.__oslogstring: 0x142
   __TEXT.__unwind_info: 0x260
   __DATA_CONST.__auth_got: 0x450
-  __DATA_CONST.__got: 0x1b0
+  __DATA_CONST.__got: 0x1a8
   __DATA_CONST.__const: 0x378
   __DATA_CONST.__cfstring: 0x17e0
   __DATA_CONST.__objc_classlist: 0x20

   - /usr/lib/libmis.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 165
-  Symbols:   230
+  Symbols:   229
   CStrings:  642
 
Symbols:
- _kMISValidationOptionAllowLaunchWarning
Functions:
~ sub_89d4 : 532 -> 520
```
