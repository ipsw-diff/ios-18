## libxml2.2.dylib

> `/usr/lib/libxml2.2.dylib`

```diff

-38.18.0.0.0
-  __TEXT.__text: 0xc9c74
+38.19.1.0.0
+  __TEXT.__text: 0xc9e7c
   __TEXT.__auth_stubs: 0x760
-  __TEXT.__cstring: 0x1987e
+  __TEXT.__cstring: 0x1993e
   __TEXT.__const: 0x38b0
   __TEXT.__oslogstring: 0xa2
-  __TEXT.__unwind_info: 0x1b48
+  __TEXT.__unwind_info: 0x1b50
   __DATA_CONST.__got: 0x50
   __DATA_CONST.__const: 0x7a98
   __AUTH_CONST.__auth_got: 0x3b0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 2607
-  Symbols:   3092
-  CStrings:  3976
+  Functions: 2608
+  Symbols:   3093
+  CStrings:  3979
 
Symbols:
+ _xmlSchemaIDCRegisterMatchers
Functions:
~ _xmlAddChild : 504 -> 540
~ _xmlSchemaFixupComponents : 3860 -> 3980
~ _xmlSchemaValidateElem : 3472 -> 3160
+ _xmlSchemaIDCRegisterMatchers
~ _xmlSchemaVAttributesSimple : 120 -> 152
~ _xmlSchemaXPathProcessHistory : 2840 -> 3012
CStrings:
+ "calling xmlSchemaIDCRegisterMatchers()"
+ "negative `pos` at selector (`depth >= matcher->depth` invariant violated)"
+ "negative `pos` in field handler (`depth >= matcher->depth` invariant violated)"
```
