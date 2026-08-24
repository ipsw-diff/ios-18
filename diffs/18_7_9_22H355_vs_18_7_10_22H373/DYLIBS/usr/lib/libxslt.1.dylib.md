## libxslt.1.dylib

> `/usr/lib/libxslt.1.dylib`

```diff

-21.11.0.0.0
-  __TEXT.__text: 0x22950
-  __TEXT.__auth_stubs: 0xdd0
+21.11.2.0.0
+  __TEXT.__text: 0x22938
+  __TEXT.__auth_stubs: 0xdb0
   __TEXT.__cstring: 0x7198
   __TEXT.__const: 0xc0
   __TEXT.__unwind_info: 0x4e0
   __DATA_CONST.__got: 0x50
   __DATA_CONST.__const: 0x228
-  __AUTH_CONST.__auth_got: 0x6e8
+  __AUTH_CONST.__auth_got: 0x6d8
   __AUTH_CONST.__const: 0x40
   __DATA.__data: 0x28
   __DATA.__bss: 0x461

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libxml2.2.dylib
   Functions: 390
-  Symbols:   662
+  Symbols:   660
   CStrings:  892
 
Symbols:
+ _arc4random_buf
- _random
- _srandom
- _time
Functions:
~ _xsltAttribute : 1300 -> 1316
~ __initBaseValue : 68 -> 16
~ _xsltParseTemplateContent : 1160 -> 1172
```
