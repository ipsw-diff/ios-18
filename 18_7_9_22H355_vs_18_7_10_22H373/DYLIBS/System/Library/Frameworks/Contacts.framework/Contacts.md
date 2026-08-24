## Contacts

> `/System/Library/Frameworks/Contacts.framework/Contacts`

```diff

-3770.700.1.0.0
-  __TEXT.__text: 0x18f420
+3843.100.1.0.0
+  __TEXT.__text: 0x190010
   __TEXT.__auth_stubs: 0x3040
-  __TEXT.__objc_methlist: 0x18358
+  __TEXT.__objc_methlist: 0x18380
   __TEXT.__const: 0x1bc8
   __TEXT.__gcc_except_tab: 0x3490
-  __TEXT.__cstring: 0xc042
-  __TEXT.__oslogstring: 0x96fa
+  __TEXT.__cstring: 0xc052
+  __TEXT.__oslogstring: 0x97da
   __TEXT.__dlopen_cstrs: 0x394
   __TEXT.__ustring: 0x12
   __TEXT.__constg_swiftt: 0xc7c

   __TEXT.__swift5_capture: 0x50c
   __TEXT.__swift_as_entry: 0x68
   __TEXT.__swift_as_ret: 0x5c
-  __TEXT.__unwind_info: 0x71f0
+  __TEXT.__unwind_info: 0x7218
   __TEXT.__eh_frame: 0x2198
   __TEXT.__objc_classname: 0x3aaa
-  __TEXT.__objc_methname: 0x26f4b
+  __TEXT.__objc_methname: 0x26fbf
   __TEXT.__objc_methtype: 0x4991
-  __TEXT.__objc_stubs: 0x1bd20
-  __DATA_CONST.__got: 0x19d8
+  __TEXT.__objc_stubs: 0x1bdc0
+  __DATA_CONST.__got: 0x19e0
   __DATA_CONST.__const: 0x5ba0
   __DATA_CONST.__objc_classlist: 0xef0
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x270
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8890
+  __DATA_CONST.__objc_selrefs: 0x88b0
   __DATA_CONST.__objc_protorefs: 0xb8
   __DATA_CONST.__objc_superrefs: 0x898
   __DATA_CONST.__objc_arraydata: 0x258
   __AUTH_CONST.__auth_got: 0x1830
-  __AUTH_CONST.__const: 0x6020
+  __AUTH_CONST.__const: 0x6040
   __AUTH_CONST.__cfstring: 0xd140
-  __AUTH_CONST.__objc_const: 0x269c8
-  __AUTH_CONST.__objc_intobj: 0x570
+  __AUTH_CONST.__objc_const: 0x269e8
+  __AUTH_CONST.__objc_intobj: 0x558
   __AUTH_CONST.__objc_arrayobj: 0x1c8
   __AUTH.__objc_data: 0x4e18
   __AUTH.__data: 0x598
   __DATA.__objc_ivar: 0x105c
   __DATA.__data: 0x2490
-  __DATA.__bss: 0x2170
+  __DATA.__bss: 0x2180
   __DATA.__common: 0x80
   __DATA_DIRTY.__objc_data: 0x51e0
   __DATA_DIRTY.__data: 0x20

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 11332
-  Symbols:   20964
-  CStrings:  9328
+  Functions: 11344
+  Symbols:   20972
+  CStrings:  9338
 
Symbols:
+ +[CNContactProviderSupportManager log]
+ -[CNContactProviderSupportManager hasSPIEntitlement]
+ -[CNContactProviderSupportManager isProviderExtensionEnabled]
+ _CNEntitlementNameContactsFrameworkSPI
+ _OBJC_IVAR_$_CNContactProviderSupportManager._hasSPIEntitlement
+ ___38+[CNContactProviderSupportManager log]_block_invoke
+ _objc_msgSend$auditToken:hasBooleanEntitlement:error:
+ _objc_msgSend$audit_token
+ _objc_msgSend$hasSPIEntitlement
+ _objc_msgSend$isExtensionEnabledWith:
+ _objc_msgSend$isProviderExtensionEnabled
- -[CNContactProviderSupportiOSDataMapper defaultContainerIdentifierImpl]
- _OBJC_IVAR_$_CNContactProviderSupportiOSDataMapper._cachedContainerIdentifier
- ___67-[CNContactProviderSupportiOSDataMapper defaultContainerIdentifier]_block_invoke
CStrings:
+ "%@ has no SPI access to CNContactProviderSupportDomainCommand %@"
+ "%@ has no SPI access to set CNContactProviderSupportDomainCommand.bundleIdentifier (%@)"
+ "Failed to check SPI entitlement, error: %@"
+ "No provider access allowed"
+ "TB,R,N,V_hasSPIEntitlement"
+ "_hasSPIEntitlement"
+ "auditToken:hasBooleanEntitlement:error:"
+ "audit_token"
+ "hasSPIEntitlement"
+ "isProviderExtensionEnabled"
+ "support-manager"
- "_cachedContainerIdentifier"
```
