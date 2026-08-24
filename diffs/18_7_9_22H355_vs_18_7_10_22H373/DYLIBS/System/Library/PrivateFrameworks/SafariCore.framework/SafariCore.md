## SafariCore

> `/System/Library/PrivateFrameworks/SafariCore.framework/SafariCore`

```diff

-621.9.1.10.1
-  __TEXT.__text: 0xfc43c
-  __TEXT.__auth_stubs: 0x27e0
+621.10.1.10.2
+  __TEXT.__text: 0xfd3b8
+  __TEXT.__auth_stubs: 0x27d0
   __TEXT.__objc_methlist: 0xa9ac
   __TEXT.__const: 0x1904
-  __TEXT.__gcc_except_tab: 0x6388
+  __TEXT.__gcc_except_tab: 0x63e0
   __TEXT.__cstring: 0x10a25
   __TEXT.__ustring: 0x27de
   __TEXT.__oslogstring: 0x9952

   __TEXT.__swift_as_entry: 0x90
   __TEXT.__swift_as_ret: 0x70
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x5620
+  __TEXT.__unwind_info: 0x5668
   __TEXT.__eh_frame: 0x1e60
   __TEXT.__objc_classname: 0x1864
-  __TEXT.__objc_methname: 0x21a53
+  __TEXT.__objc_methname: 0x219cc
   __TEXT.__objc_methtype: 0x3b9b
   __TEXT.__objc_stubs: 0x10980
   __DATA_CONST.__got: 0xcc8
-  __DATA_CONST.__const: 0x4ba0
+  __DATA_CONST.__const: 0x4bf0
   __DATA_CONST.__objc_classlist: 0x560
   __DATA_CONST.__objc_catlist: 0x150
   __DATA_CONST.__objc_protolist: 0x158

   __DATA_CONST.__objc_protorefs: 0x80
   __DATA_CONST.__objc_superrefs: 0x438
   __DATA_CONST.__objc_arraydata: 0x2740
-  __AUTH_CONST.__auth_got: 0x1408
+  __AUTH_CONST.__auth_got: 0x1400
   __AUTH_CONST.__const: 0x3e98
   __AUTH_CONST.__cfstring: 0x17b40
-  __AUTH_CONST.__objc_const: 0x11138
+  __AUTH_CONST.__objc_const: 0x111d8
   __AUTH_CONST.__objc_intobj: 0x390
   __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH_CONST.__objc_arrayobj: 0x570
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH.__objc_data: 0xb28
   __AUTH.__data: 0x318
-  __DATA.__objc_ivar: 0xad8
+  __DATA.__objc_ivar: 0xaec
   __DATA.__data: 0x1318
   __DATA.__bss: 0x2430
   __DATA.__common: 0x18

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 5968
-  Symbols:   11031
-  CStrings:  8831
+  Functions: 5988
+  Symbols:   11051
+  CStrings:  8830
 
Symbols:
+ +[WBSTOTPGenerator keyDataForBase32EncodedString:]
+ _OBJC_IVAR_$_WBSAppIDsToDomainsAssociationManager._queue
+ _OBJC_IVAR_$_WBSChangePasswordURLManager._queue
+ _OBJC_IVAR_$_WBSPasswordAuditingEligibleDomainsManager._queue
+ _OBJC_IVAR_$_WBSPasswordGenerationManager._passwordRulesByDomain
+ _OBJC_IVAR_$_WBSPasswordGenerationManager._queue
+ _WBSReleaseOnMainQueueImpl.lock
+ _WBSReleaseOnMainQueueImpl.objectList
+ ___50+[WBSTOTPGenerator keyDataForBase32EncodedString:]_block_invoke
+ ___51-[WBSAppIDsToDomainsAssociationManager description]_block_invoke
+ ___55-[WBSAppIDsToDomainsAssociationManager appIDsToDomains]_block_invoke
+ ___55-[WBSChangePasswordURLManager changePasswordURLStrings]_block_invoke
+ ___59-[WBSAppIDsToDomainsAssociationManager setAppIDsToDomains:]_block_invoke
+ ___59-[WBSChangePasswordURLManager setChangePasswordURLStrings:]_block_invoke
+ ___60-[WBSPasswordGenerationManager passwordRequirementsByDomain]_block_invoke
+ ___61-[WBSPasswordGenerationManager defaultRequirementsForDomain:]_block_invoke
+ ___64-[WBSPasswordGenerationManager setPasswordRequirementsByDomain:]_block_invoke
+ ___67-[WBSChangePasswordURLManager changePasswordURLForHighLevelDomain:]_block_invoke
+ ___81-[WBSAppIDsToDomainsAssociationManager domainsWithAssociatedCredentialsForAppID:]_block_invoke
+ ___81-[WBSPasswordAuditingEligibleDomainsManager domainsIneligibleForPasswordAuditing]_block_invoke
+ ___85-[WBSPasswordAuditingEligibleDomainsManager setDomainsIneligibleForPasswordAuditing:]_block_invoke
+ ___block_descriptor_48_ea8_32s40r_e5_v8?0lr40l8s32l8
+ ___block_descriptor_56_ea8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
+ _keyDataForBase32EncodedString:.inverseAlphabet
+ _keyDataForBase32EncodedString:.onceToken
+ _objc_msgSend$keyDataForBase32EncodedString:
- +[WBSTOTPGenerator _keyDataForBase32EncodedString:]
- ___51+[WBSTOTPGenerator _keyDataForBase32EncodedString:]_block_invoke
- __keyDataForBase32EncodedString:.inverseAlphabet
- __keyDataForBase32EncodedString:.onceToken
- _objc_msgSend$_keyDataForBase32EncodedString:
- _objc_setProperty_atomic_copy
CStrings:
+ "T@\"NSDictionary\",C"
+ "T@\"NSSet\",C"
+ "_passwordRulesByDomain"
+ "keyDataForBase32EncodedString:"
- "T@\"NSDictionary\",C,N,V_appIDsToDomains"
- "T@\"NSDictionary\",C,N,V_passwordRequirementsByDomain"
- "T@\"NSDictionary\",C,V_changePasswordURLStrings"
- "T@\"NSSet\",C,V_domainsIneligibleForPasswordAuditing"
- "_keyDataForBase32EncodedString:"
```
