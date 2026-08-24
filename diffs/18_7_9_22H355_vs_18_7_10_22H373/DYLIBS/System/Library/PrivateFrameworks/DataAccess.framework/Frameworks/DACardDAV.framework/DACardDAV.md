## DACardDAV

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DACardDAV.framework/DACardDAV`

```diff

-2673.7.2.0.0
-  __TEXT.__text: 0x9fbc
-  __TEXT.__auth_stubs: 0x5c0
-  __TEXT.__objc_methlist: 0x13a4
+2673.7.3.0.0
+  __TEXT.__text: 0xa5f0
+  __TEXT.__auth_stubs: 0x5f0
+  __TEXT.__objc_methlist: 0x13c4
   __TEXT.__const: 0x40
   __TEXT.__gcc_except_tab: 0x20
-  __TEXT.__cstring: 0x5c9
-  __TEXT.__oslogstring: 0x6e8
-  __TEXT.__unwind_info: 0x2f8
-  __TEXT.__objc_classname: 0x248
-  __TEXT.__objc_methname: 0x2cc8
+  __TEXT.__cstring: 0x5d5
+  __TEXT.__oslogstring: 0x72d
+  __TEXT.__unwind_info: 0x308
+  __TEXT.__objc_classname: 0x256
+  __TEXT.__objc_methname: 0x2dc5
   __TEXT.__objc_methtype: 0x886
-  __TEXT.__objc_stubs: 0x28c0
-  __DATA_CONST.__got: 0x3c8
+  __TEXT.__objc_stubs: 0x2a60
+  __DATA_CONST.__got: 0x3e0
   __DATA_CONST.__const: 0x208
-  __DATA_CONST.__objc_classlist: 0x68
+  __DATA_CONST.__objc_classlist: 0x70
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe50
+  __DATA_CONST.__objc_selrefs: 0xeb8
   __DATA_CONST.__objc_superrefs: 0x58
-  __AUTH_CONST.__auth_got: 0x2f0
+  __AUTH_CONST.__auth_got: 0x308
   __AUTH_CONST.__const: 0x100
-  __AUTH_CONST.__cfstring: 0x520
-  __AUTH_CONST.__objc_const: 0x2dc8
-  __AUTH.__objc_data: 0x2d0
+  __AUTH_CONST.__cfstring: 0x5a0
+  __AUTH_CONST.__objc_const: 0x2e58
+  __AUTH.__objc_data: 0x320
   __DATA.__objc_ivar: 0x8c
   __DATA.__data: 0x480
   __DATA.__bss: 0x10
   __DATA_DIRTY.__objc_data: 0x140
   - /System/Library/Frameworks/Accounts.framework/Accounts
+  - /System/Library/Frameworks/CFNetwork.framework/CFNetwork
   - /System/Library/Frameworks/Contacts.framework/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 299
-  Symbols:   1057
-  CStrings:  736
+  Functions: 304
+  Symbols:   1085
+  CStrings:  755
 
Symbols:
+ +[DAURLSecurity hostSharesRegistrableDomain:with:]
+ +[DAURLSecurity photoURL:isAllowedForServerHost:]
+ _DAURLSecurityIsIPLiteral
+ _DAURLSecurityNormalize
+ _DAURLSecurityRegistrableDomain
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_DAURLSecurity
+ _OBJC_CLASS_$_NSURLComponents
+ _OBJC_METACLASS_$_DAURLSecurity
+ __CFHostGetTopLevelDomain
+ __OBJC_$_CLASS_METHODS_DAURLSecurity
+ __OBJC_CLASS_RO_$_DAURLSecurity
+ __OBJC_METACLASS_RO_$_DAURLSecurity
+ _inet_pton
+ _objc_msgSend$UTF8String
+ _objc_msgSend$componentsSeparatedByString:
+ _objc_msgSend$encodedHost
+ _objc_msgSend$hasPrefix:
+ _objc_msgSend$hasSuffix:
+ _objc_msgSend$hostSharesRegistrableDomain:with:
+ _objc_msgSend$lastObject
+ _objc_msgSend$lowercaseString
+ _objc_msgSend$photoURL:isAllowedForServerHost:
+ _objc_msgSend$stringByAppendingString:
+ _objc_msgSend$stringWithUTF8String:
+ _objc_msgSend$substringToIndex:
+ _objc_msgSend$substringWithRange:
+ _strlen
CStrings:
+ "%@.%@"
+ "."
+ "DAURLSecurity"
+ "Refusing to fetch photo from %@; host does not match server host %@."
+ "UTF8String"
+ "["
+ "]"
+ "componentsSeparatedByString:"
+ "encodedHost"
+ "hasPrefix:"
+ "hasSuffix:"
+ "hostSharesRegistrableDomain:with:"
+ "lastObject"
+ "lowercaseString"
+ "photoURL:isAllowedForServerHost:"
+ "stringByAppendingString:"
+ "stringWithUTF8String:"
+ "substringToIndex:"
+ "substringWithRange:"
```
