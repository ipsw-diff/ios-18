## Books

> `/System/Library/SyncBundles/Books.syncBundle/Books`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__data`

```diff

-136.0.0.0.0
-  __TEXT.__text: 0x12ff8
-  __TEXT.__auth_stubs: 0x390
-  __TEXT.__objc_stubs: 0x29c0
-  __TEXT.__objc_methlist: 0xed4
+137.0.0.0.0
+  __TEXT.__text: 0x13a00
+  __TEXT.__auth_stubs: 0x3e0
+  __TEXT.__objc_stubs: 0x2a40
+  __TEXT.__objc_methlist: 0xf24
   __TEXT.__const: 0xb8
-  __TEXT.__objc_methname: 0x2b82
-  __TEXT.__oslogstring: 0x26b3
-  __TEXT.__objc_classname: 0x1c3
+  __TEXT.__objc_methname: 0x2be0
+  __TEXT.__oslogstring: 0x286c
+  __TEXT.__objc_classname: 0x1e4
   __TEXT.__objc_methtype: 0x869
-  __TEXT.__cstring: 0xb27
+  __TEXT.__cstring: 0xb48
   __TEXT.__gcc_except_tab: 0x4fc
-  __TEXT.__unwind_info: 0x3e8
-  __DATA_CONST.__auth_got: 0x1d8
+  __TEXT.__unwind_info: 0x428
+  __DATA_CONST.__auth_got: 0x200
   __DATA_CONST.__got: 0x198
-  __DATA_CONST.__const: 0x450
-  __DATA_CONST.__cfstring: 0xf80
-  __DATA_CONST.__objc_classlist: 0x88
+  __DATA_CONST.__const: 0x470
+  __DATA_CONST.__cfstring: 0xfc0
+  __DATA_CONST.__objc_classlist: 0x98
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__objc_intobj: 0x18
-  __DATA.__objc_const: 0x13c8
-  __DATA.__objc_selrefs: 0xce0
+  __DATA.__objc_const: 0x14e8
+  __DATA.__objc_selrefs: 0xd00
   __DATA.__objc_ivar: 0x90
-  __DATA.__objc_data: 0x550
+  __DATA.__objc_data: 0x5f0
   __DATA.__data: 0x140
-  __DATA.__bss: 0x38
+  __DATA.__bss: 0x48
   - /System/Library/Frameworks/CoreData.framework/CoreData
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /System/Library/PrivateFrameworks/StoreServices.framework/StoreServices
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 349
-  Symbols:   227
-  CStrings:  944
+  Functions: 366
+  Symbols:   236
+  CStrings:  965
 
Symbols:
+ _OBJC_CLASS_$_BCFileOperation
+ _OBJC_CLASS_$_BCFilePathHelper
+ _OBJC_METACLASS_$_BCFileOperation
+ _OBJC_METACLASS_$_BCFilePathHelper
+ ___error
+ _fcopyfile
+ _fstat
+ _realpath$DARWIN_EXTSN
+ _unlinkat
CStrings:
+ "/private"
+ "/private/var"
+ "/var"
+ "/var/"
+ "20:20:41"
+ "BCFileOperation"
+ "BCFilePathHelper"
+ "Jul  6 2026"
+ "_copyBooksFileAtPath:toPath:"
+ "_unlinkBooksFileAtPath:"
+ "copyRegularFile: %@ -> %@"
+ "copyRegularFile: empty path src=[%@] dst=[%@]"
+ "copyRegularFile: fcopyfile [%@ -> %@] failed errno=%d"
+ "copyRegularFile: fstat src [%@] failed errno=%d"
+ "copyRegularFile: open dst [%@] failed errno=%d"
+ "copyRegularFile: open src [%@] failed errno=%d"
+ "copyRegularFile: src [%@] absent — skipping"
+ "copyRegularFile: src [%@] is not a regular file (mode=0%o)"
+ "copyRegularFileAtPath:toPath:"
+ "pathByReplacingVarPrefix:"
+ "unlink: %@"
+ "unlink: empty path"
+ "unlink: unlinkat [%@] failed errno=%d"
+ "unlinkAtPath:"
- "19:38:13"
- "Jul 20 2025"
- "copyItemAtPath:toPath:error:"
```
