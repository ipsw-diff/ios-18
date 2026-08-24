## SafariShared

> `/System/Library/PrivateFrameworks/SafariShared.framework/SafariShared`

```diff

-621.9.1.10.1
-  __TEXT.__text: 0x1a0e00
+621.10.1.10.2
+  __TEXT.__text: 0x1a1608
   __TEXT.__auth_stubs: 0x1cc0
-  __TEXT.__objc_methlist: 0x13afc
+  __TEXT.__objc_methlist: 0x13b64
   __TEXT.__const: 0x671ea
-  __TEXT.__gcc_except_tab: 0x1f074
-  __TEXT.__cstring: 0x1d9b0
-  __TEXT.__ustring: 0xcb18
+  __TEXT.__gcc_except_tab: 0x1f138
+  __TEXT.__cstring: 0x1d3c0
+  __TEXT.__ustring: 0xcd7e
   __TEXT.__oslogstring: 0x11c0d
   __TEXT.__dlopen_cstrs: 0x25f
   __TEXT.__constg_swiftt: 0x8c

   __TEXT.__swift5_reflstr: 0x1c
   __TEXT.__swift5_fieldmd: 0x2c
   __TEXT.__swift5_types: 0x8
-  __TEXT.__unwind_info: 0xb500
-  __TEXT.__objc_classname: 0x353a
-  __TEXT.__objc_methname: 0x390e1
-  __TEXT.__objc_methtype: 0xc876
-  __TEXT.__objc_stubs: 0x1f1e0
+  __TEXT.__unwind_info: 0xb568
+  __TEXT.__objc_classname: 0x356e
+  __TEXT.__objc_methname: 0x39340
+  __TEXT.__objc_methtype: 0xc89d
+  __TEXT.__objc_stubs: 0x1f420
   __DATA_CONST.__got: 0x15d0
-  __DATA_CONST.__const: 0x14e48
-  __DATA_CONST.__objc_classlist: 0xbd8
+  __DATA_CONST.__const: 0x14e90
+  __DATA_CONST.__objc_classlist: 0xbe0
   __DATA_CONST.__objc_catlist: 0x98
-  __DATA_CONST.__objc_protolist: 0x288
+  __DATA_CONST.__objc_protolist: 0x290
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xac58
+  __DATA_CONST.__objc_selrefs: 0xacd8
   __DATA_CONST.__objc_protorefs: 0x98
-  __DATA_CONST.__objc_superrefs: 0x940
+  __DATA_CONST.__objc_superrefs: 0x948
   __DATA_CONST.__objc_arraydata: 0xa20
   __AUTH_CONST.__auth_got: 0xe78
   __AUTH_CONST.__const: 0x32e0
-  __AUTH_CONST.__cfstring: 0x19060
-  __AUTH_CONST.__objc_const: 0x23b98
+  __AUTH_CONST.__cfstring: 0x19220
+  __AUTH_CONST.__objc_const: 0x23cb0
   __AUTH_CONST.__objc_intobj: 0x588
   __AUTH_CONST.__objc_arrayobj: 0x2a0
   __AUTH_CONST.__objc_dictobj: 0x140
   __AUTH_CONST.__objc_doubleobj: 0xa0
-  __AUTH.__objc_data: 0x41d8
+  __AUTH.__objc_data: 0x4228
   __AUTH.__data: 0xe0
-  __DATA.__objc_ivar: 0x16f4
-  __DATA.__data: 0x31a0
+  __DATA.__objc_ivar: 0x16f8
+  __DATA.__data: 0x3200
   __DATA.__bss: 0xad0
   __DATA_DIRTY.__objc_data: 0x34a8
   __DATA_DIRTY.__data: 0x10

   - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking
   - /System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter
   - /System/Library/PrivateFrameworks/Trial.framework/Trial
+  - /System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore
   - /System/Library/PrivateFrameworks/UsageTracking.framework/UsageTracking
   - /usr/lib/libCTGreenTeaLogger.dylib
   - /usr/lib/libMobileGestalt.dylib

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/swift/libswiftAVFoundation.dylib
+  - /usr/lib/swift/libswiftAccelerate.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/swift/libswiftCoreAudio.dylib
   - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftCoreImage.dylib
   - /usr/lib/swift/libswiftCoreLocation.dylib
   - /usr/lib/swift/libswiftCoreMIDI.dylib
   - /usr/lib/swift/libswiftCoreMedia.dylib
   - /usr/lib/swift/libswiftDarwin.dylib
+  - /usr/lib/swift/libswiftDataDetection.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftIntents.dylib
   - /usr/lib/swift/libswiftMetal.dylib

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 9984
-  Symbols:   21036
-  CStrings:  13822
+  Functions: 9988
+  Symbols:   21083
+  CStrings:  13856
 
Symbols:
+ -[WBSBrowserTabCompletionProvider _compareTabMatch:otherTabMatch:usingSelectedTabInfo:]
+ -[WBSBrowserTabCompletionProvider _distanceFromSelectedTabForTabMatch:usingSelectedTabInfo:]
+ -[WBSCertificateWarningPageContext _bypassFeatureTitleText]
+ -[WBSCertificateWarningPageContext _bypassFeatureWarningText]
+ -[WBSCertificateWarningPageContext _pageLoadedJSUsingRTL:]
+ -[WBSCertificateWarningPageContext _sanitizedJavaScriptStringContentFromString:]
+ -[WBSCertificateWarningPageContext generateHTMLFromDataAtURL:withBypassFeatureButtonText:usingRTL:]
+ -[WBSWarningPageCommandHandler .cxx_destruct]
+ -[WBSWarningPageCommandHandler initWithWarningPageHandler:]
+ -[WBSWarningPageCommandHandler userContentController:didReceiveScriptMessage:]
+ -[WBSWarningPageCommandHandler warningPageHandler]
+ _OBJC_CLASS_$_WBSWarningPageCommandHandler
+ _OBJC_IVAR_$_WBSWarningPageCommandHandler._warningPageHandler
+ _OBJC_METACLASS_$_WBSWarningPageCommandHandler
+ __OBJC_$_INSTANCE_METHODS_WBSWarningPageCommandHandler
+ __OBJC_$_INSTANCE_VARIABLES_WBSWarningPageCommandHandler
+ __OBJC_$_PROP_LIST_WBSWarningPageCommandHandler
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_WKScriptMessageHandler
+ __OBJC_$_PROTOCOL_METHOD_TYPES_WKScriptMessageHandler
+ __OBJC_$_PROTOCOL_REFS_WKScriptMessageHandler
+ __OBJC_CLASS_PROTOCOLS_$_WBSWarningPageCommandHandler
+ __OBJC_CLASS_RO_$_WBSWarningPageCommandHandler
+ __OBJC_LABEL_PROTOCOL_$_WKScriptMessageHandler
+ __OBJC_METACLASS_RO_$_WBSWarningPageCommandHandler
+ __OBJC_PROTOCOL_$_WKScriptMessageHandler
+ __ZN3WTF20VectorTypeOperationsI9SortEntryE4moveEPS1_S3_S3_
+ __ZN3WTF20VectorTypeOperationsI9SortEntryE8destructEPS1_S3_
+ __ZN3WTF22IdentityHashTranslatorIN12SafariShared29URLCompletionEntryValueTraitsENS1_22URLCompletionEntryHashEE9translateINS1_18URLCompletionEntryENS1_21URLCompletionEntryKeyEZNS_9HashTableIS7_S6_NS1_30URLCompletionEntryKeyExtractorES3_S2_NS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE3addILNS_17ShouldValidateKeyE1EEENS_18HashTableAddResultINS_17HashTableIteratorISC_S7_S6_S9_S3_S2_SA_EEEEOS6_EUlvE_EEvRT_RKT0_RKT1_
+ __ZN3WTF6VectorIdLm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEEC2Em
+ __ZN3WTF6VectorIfLm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEEC2Em
+ __ZN3WTF7HashMapIP15OpaqueJSContextP21OpaqueJSWeakObjectMapNS_11DefaultHashIS2_EENS_10HashTraitsIS2_EENS7_IS4_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE3addIS4_EENS_18HashTableAddResultINS_17HashTableIteratorINS_9HashTableIS2_NS_12KeyValuePairIS2_S4_EENS_24KeyValuePairKeyExtractorISJ_EES6_NSD_18KeyValuePairTraitsES8_SC_EES2_SJ_SL_S6_SM_S8_EEEERKS2_OT_
+ __ZN3WTF7HashMapIP23OpaqueFormAutoFillFrameNSt3__110unique_ptrIN12SafariShared13FrameMetadataENS3_14default_deleteIS6_EEEENS_11DefaultHashIS2_EENS_10HashTraitsIS2_EENSC_IS9_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE3addIDnEENS_18HashTableAddResultINS_17HashTableIteratorINS_9HashTableIS2_NS_12KeyValuePairIS2_S9_EENS_24KeyValuePairKeyExtractorISO_EESB_NSI_18KeyValuePairTraitsESD_SH_EES2_SO_SQ_SB_SR_SD_EEEEOS2_OT_
+ __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE11validateKeyILNS_17ShouldValidateKeyE1EEEvRKS3_
+ __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE15deallocateTableEPS3_
+ __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE3addILNS_17ShouldValidateKeyE1EEENS_18HashTableAddResultINS_17HashTableIteratorIS9_S2_S3_S4_S5_S6_S7_EEEEOS3_
+ __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE4findINS_22IdentityHashTranslatorIS6_S5_EELNS_17ShouldValidateKeyE1ES2_EENS_17HashTableIteratorIS9_S2_S3_S4_S5_S6_S7_EERKT1_
+ __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE6expandEPS3_
+ __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE6lookupILNS_17ShouldValidateKeyE1EEEPS3_RKS2_
+ __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE6rehashENS_7CheckedIjNS_15CrashOnOverflowEEEPS3_
+ __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE6removeEPS3_
+ __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESD_SH_E17lookupForReinsertERKS2_
+ __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESD_SH_E4findINS_22IdentityHashTranslatorISJ_SA_EELSG_1ES2_EENS_17HashTableIteratorISK_S2_S6_S8_SA_SJ_SD_EERKT1_
+ __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESD_SH_E5beginEv
+ __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESD_SH_E6expandEPS6_
+ __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESD_SH_E6rehashENS_7CheckedIjNS_15CrashOnOverflowEEEPS6_
+ __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESD_SH_E6removeEPS6_
+ __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESI_SM_E15deallocateTableEPSB_
+ __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESI_SM_E17lookupForReinsertERKS2_
+ __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESI_SM_E4findINS_22IdentityHashTranslatorISO_SF_EELSL_1ES2_EENS_17HashTableIteratorISP_S2_SB_SD_SF_SO_SI_EERKT1_
+ __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESI_SM_E6expandEPSB_
+ __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESI_SM_E6rehashENS_7CheckedIjNS_15CrashOnOverflowEEEPSB_
+ __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESI_SM_E6removeEPSB_
+ __ZNK12SafariShared25URLCompletionEntryBuilder15buildEntryInMapERN3WTF9HashTableINS_21URLCompletionEntryKeyENS_18URLCompletionEntryENS_30URLCompletionEntryKeyExtractorENS_22URLCompletionEntryHashENS_29URLCompletionEntryValueTraitsENS_27URLCompletionEntryKeyTraitsENS1_10FastMallocEEEb
+ __ZNK3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE17makeConstIteratorEPS3_
+ __ZNK3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE4findINS_22IdentityHashTranslatorIS6_S5_EELNS_17ShouldValidateKeyE1ES2_EENS_22HashTableConstIteratorIS9_S2_S3_S4_S5_S6_S7_EERKT1_
+ __ZNK3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsENS_10FastMallocEE5beginEv
+ __ZNK3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESI_SM_E8containsINS_22IdentityHashTranslatorISO_SF_EELSL_1ES2_EEbRKT1_
+ ___99-[WBSCertificateWarningPageContext generateHTMLFromDataAtURL:withBypassFeatureButtonText:usingRTL:]_block_invoke
+ ___block_descriptor_40_ea8_32s_e54_"NSString"32?0"NSString"8"NSString"16"NSString"24ls32l8
+ ___block_descriptor_48_ea8_32s40s_e71_q24?0"WBSBrowserTabCompletionMatch"8"WBSBrowserTabCompletionMatch"16ls32l8s40l8
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftAccelerate_$_SafariShared
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreImage_$_SafariShared
+ __swift_FORCE_LOAD_$_swiftDataDetection
+ __swift_FORCE_LOAD_$_swiftDataDetection_$_SafariShared
+ __swift_FORCE_LOAD_$_swiftUIKit
+ __swift_FORCE_LOAD_$_swiftUIKit_$_SafariShared
+ _objc_msgSend$_bypassFeatureTitleText
+ _objc_msgSend$_bypassFeatureWarningText
+ _objc_msgSend$_compareTabMatch:otherTabMatch:usingSelectedTabInfo:
+ _objc_msgSend$_distanceFromSelectedTabForTabMatch:usingSelectedTabInfo:
+ _objc_msgSend$_pageLoadedJSUsingRTL:
+ _objc_msgSend$_sanitizedJavaScriptStringContentFromString:
+ _objc_msgSend$body
+ _objc_msgSend$canGoBack
+ _objc_msgSend$clockSkew
+ _objc_msgSend$expiredCerticateDescription
+ _objc_msgSend$failingURL
+ _objc_msgSend$goBackButtonClicked
+ _objc_msgSend$numberOfDaysInvalid
+ _objc_msgSend$openClockSettings
+ _objc_msgSend$showCertificateInformation
+ _objc_msgSend$stringWithContentsOfURL:encoding:error:
+ _objc_msgSend$visitInsecureWebsite
+ _objc_msgSend$visitInsecureWebsiteWithTemporaryBypass
+ _objc_msgSend$visitWebsiteWithoutPrivateRelay
+ _objc_msgSend$warningCategory
- +[WBSCertificateWarningPageContext supportsSecureCoding]
- -[WBSBrowserTabCompletionProvider _compareTabMatch:otherTabMatch:]
- -[WBSBrowserTabCompletionProvider _distanceFromSelectedTabForTabMatch:]
- -[WBSCertificateWarningPageContext encodeWithCoder:]
- -[WBSCertificateWarningPageContext initWithCoder:]
- __OBJC_$_CLASS_PROP_LIST_WBSCertificateWarningPageContext
- __OBJC_CLASS_PROTOCOLS_$_WBSCertificateWarningPageContext
- __ZN3WTF11VectorMoverILb0E9SortEntryE4moveEPS1_S3_S3_
- __ZN3WTF16VectorDestructorILb1E9SortEntryE8destructEPS1_S3_
- __ZN3WTF22IdentityHashTranslatorIN12SafariShared29URLCompletionEntryValueTraitsENS1_22URLCompletionEntryHashEE9translateINS1_18URLCompletionEntryENS1_21URLCompletionEntryKeyEZNS_9HashTableIS7_S6_NS1_30URLCompletionEntryKeyExtractorES3_S2_NS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE3addEOS6_EUlvE_EEvRT_RKT0_RKT1_
- __ZN3WTF7HashMapIP15OpaqueJSContextP21OpaqueJSWeakObjectMapNS_11DefaultHashIS2_EENS_10HashTraitsIS2_EENS7_IS4_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE3addIS4_EENS_18HashTableAddResultINS_17HashTableIteratorINS_9HashTableIS2_NS_12KeyValuePairIS2_S4_EENS_24KeyValuePairKeyExtractorISI_EES6_NSC_18KeyValuePairTraitsES8_LSB_1EEES2_SI_SK_S6_SL_S8_EEEERKS2_OT_
- __ZN3WTF7HashMapIP23OpaqueFormAutoFillFrameNSt3__110unique_ptrIN12SafariShared13FrameMetadataENS3_14default_deleteIS6_EEEENS_11DefaultHashIS2_EENS_10HashTraitsIS2_EENSC_IS9_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE3addIDnEENS_18HashTableAddResultINS_17HashTableIteratorINS_9HashTableIS2_NS_12KeyValuePairIS2_S9_EENS_24KeyValuePairKeyExtractorISN_EESB_NSH_18KeyValuePairTraitsESD_LSG_1EEES2_SN_SP_SB_SQ_SD_EEEEOS2_OT_
- __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE15deallocateTableEPS3_
- __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE17lookupForReinsertERKS2_
- __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE3addEOS3_
- __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE4findINS_22IdentityHashTranslatorIS6_S5_EES2_EENS_17HashTableIteratorIS9_S2_S3_S4_S5_S6_S7_EERKT0_
- __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE6expandEPS3_
- __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE6lookupERKS2_
- __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE6rehashENS_7CheckedIjNS_15CrashOnOverflowEEEPS3_
- __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE6removeEPS3_
- __ZN3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE8checkKeyINS_22IdentityHashTranslatorIS6_S5_EES2_EEvRKT0_
- __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESD_LSG_1EE17lookupForReinsertERKS2_
- __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESD_LSG_1EE4findINS_22IdentityHashTranslatorISI_SA_EES2_EENS_17HashTableIteratorISJ_S2_S6_S8_SA_SI_SD_EERKT0_
- __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESD_LSG_1EE5beginEv
- __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESD_LSG_1EE6expandEPS6_
- __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESD_LSG_1EE6rehashENS_7CheckedIjNS_15CrashOnOverflowEEEPS6_
- __ZN3WTF9HashTableIP15OpaqueJSContextNS_12KeyValuePairIS2_P21OpaqueJSWeakObjectMapEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS2_EENS_7HashMapIS2_S5_SA_NS_10HashTraitsIS2_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESD_LSG_1EE6removeEPS6_
- __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESI_LSL_1EE15deallocateTableEPSB_
- __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESI_LSL_1EE17lookupForReinsertERKS2_
- __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESI_LSL_1EE4findINS_22IdentityHashTranslatorISN_SF_EES2_EENS_17HashTableIteratorISO_S2_SB_SD_SF_SN_SI_EERKT0_
- __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESI_LSL_1EE6expandEPSB_
- __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESI_LSL_1EE6rehashENS_7CheckedIjNS_15CrashOnOverflowEEEPSB_
- __ZN3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESI_LSL_1EE6removeEPSB_
- __ZNK12SafariShared25URLCompletionEntryBuilder15buildEntryInMapERN3WTF9HashTableINS_21URLCompletionEntryKeyENS_18URLCompletionEntryENS_30URLCompletionEntryKeyExtractorENS_22URLCompletionEntryHashENS_29URLCompletionEntryValueTraitsENS_27URLCompletionEntryKeyTraitsELNS1_17ShouldValidateKeyE1EEEb
- __ZNK3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE17makeConstIteratorEPS3_
- __ZNK3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE4findINS_22IdentityHashTranslatorIS6_S5_EES2_EENS_22HashTableConstIteratorIS9_S2_S3_S4_S5_S6_S7_EERKT0_
- __ZNK3WTF9HashTableIN12SafariShared21URLCompletionEntryKeyENS1_18URLCompletionEntryENS1_30URLCompletionEntryKeyExtractorENS1_22URLCompletionEntryHashENS1_29URLCompletionEntryValueTraitsENS1_27URLCompletionEntryKeyTraitsELNS_17ShouldValidateKeyE1EE5beginEv
- __ZNK3WTF9HashTableIP23OpaqueFormAutoFillFrameNS_12KeyValuePairIS2_NSt3__110unique_ptrIN12SafariShared13FrameMetadataENS4_14default_deleteIS7_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESI_LSL_1EE8containsINS_22IdentityHashTranslatorISN_SF_EES2_EEbRKT0_
- ___block_descriptor_40_ea8_32s_e71_q24?0"WBSBrowserTabCompletionMatch"8"WBSBrowserTabCompletionMatch"16ls32l8
- _objc_msgSend$_compareTabMatch:otherTabMatch:
- _objc_msgSend$_distanceFromSelectedTabForTabMatch:
CStrings:
+ "/* pageLoaded */"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS18.7.Internal.sdk/usr/local/include/wtf/StdLibExtras.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS18.7.Internal.sdk/usr/local/include/wtf/Vector.h"
+ "8621.10.1.10.2"
+ "@\"<WBSCertificateWarningPageHandler>\""
+ "@\"NSString\"32@?0@\"NSString\"8@\"NSString\"16@\"NSString\"24"
+ "T@\"<WBSCertificateWarningPageHandler>\",R,W,N,V_warningPageHandler"
+ "This Connection Is Not%@Private"
+ "This website does not support connecting securely, and iCloud Private Relay is unable to protect your connection to it. By continuing to “%@” your IP address will be%@revealed."
+ "WBSWarningPageCommandHandler"
+ "WKScriptMessageHandler"
+ "\\"
+ "\\'"
+ "\\\\"
+ "_bypassFeatureTitleText"
+ "_bypassFeatureWarningText"
+ "_compareTabMatch:otherTabMatch:usingSelectedTabInfo:"
+ "_distanceFromSelectedTabForTabMatch:usingSelectedTabInfo:"
+ "_pageLoadedJSUsingRTL:"
+ "_sanitizedJavaScriptStringContentFromString:"
+ "_warningPageHandler"
+ "bool WTF::Vector<unsigned short, 256>::growImpl(size_t) [T = unsigned short, inlineCapacity = 256, OverflowHandler = WTF::CrashOnOverflow, minCapacity = 16, Malloc = WTF::FastMalloc]"
+ "bypassFeatureButtonText"
+ "bypassFeatureTitleText"
+ "bypassFeatureWarningText"
+ "certificateWarning.setTextDirection('rtl')"
+ "false"
+ "generateHTMLFromDataAtURL:withBypassFeatureButtonText:usingRTL:"
+ "goBackButtonClicked"
+ "iCloud Private Relay is unable to hide your IP address from this site. By continuing to “%@” your IP address will be%@revealed."
+ "if (window.CertificateWarning) { CertificateWarning.updateUI('%@', %zd, %s, %zu, '%@', %f); %s }"
+ "initWithWarningPageHandler:"
+ "isValidKey(value)"
+ "openClockSettings"
+ "showCertificateInformation"
+ "stringWithContentsOfURL:encoding:error:"
+ "true"
+ "userContentController:didReceiveScriptMessage:"
+ "v32@0:8@\"WKUserContentController\"16@\"WKScriptMessage\"24"
+ "validateKey"
+ "visitInsecureWebsite"
+ "visitInsecureWebsiteWithTemporaryBypass"
+ "visitWebsiteWithoutPrivateRelay"
+ "void WTF::HashTable<OpaqueFormAutoFillFrame *, WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>>, WTF::DefaultHash<OpaqueFormAutoFillFrame *>, WTF::HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>::KeyValuePairTraits, WTF::HashTraits<OpaqueFormAutoFillFrame *>>::validateKey(const ValueType &) [Key = OpaqueFormAutoFillFrame *, Value = WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>, Extractor = WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>>, HashFunctions = WTF::DefaultHash<OpaqueFormAutoFillFrame *>, Traits = WTF::HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>::KeyValuePairTraits, KeyTraits = WTF::HashTraits<OpaqueFormAutoFillFrame *>, Malloc = WTF::FastMalloc, shouldValidateKey = WTF::ShouldValidateKey::Yes]"
+ "void WTF::HashTable<OpaqueJSContext *, WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>>, WTF::DefaultHash<OpaqueJSContext *>, WTF::HashMap<OpaqueJSContext *, OpaqueJSWeakObjectMap *>::KeyValuePairTraits, WTF::HashTraits<OpaqueJSContext *>>::validateKey(const ValueType &) [Key = OpaqueJSContext *, Value = WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>, Extractor = WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>>, HashFunctions = WTF::DefaultHash<OpaqueJSContext *>, Traits = WTF::HashMap<OpaqueJSContext *, OpaqueJSWeakObjectMap *>::KeyValuePairTraits, KeyTraits = WTF::HashTraits<OpaqueJSContext *>, Malloc = WTF::FastMalloc, shouldValidateKey = WTF::ShouldValidateKey::Yes]"
+ "void WTF::memcpySpan(std::span<T, TExtent>, std::span<U, UExtent>) [T = int, TExtent = 18446744073709551615UL, U = const int, UExtent = 18446744073709551615UL]"
+ "warningPageCommand"
+ "warningPageHandler"
+ "{HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>, WTF::DefaultHash<OpaqueFormAutoFillFrame *>, WTF::HashTraits<OpaqueFormAutoFillFrame *>, WTF::HashTraits<std::unique_ptr<SafariShared::FrameMetadata>>, WTF::HashTableTraits, WTF::ShouldValidateKey::Yes, WTF::FastMalloc>=\"m_impl\"{HashTable<OpaqueFormAutoFillFrame *, WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>>, WTF::DefaultHash<OpaqueFormAutoFillFrame *>, WTF::HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>::KeyValuePairTraits, WTF::HashTraits<OpaqueFormAutoFillFrame *>, WTF::FastMalloc>=\"m_table\"^v}}"
+ "{URLCompletionEntryMap=\"_map\"{HashTable<SafariShared::URLCompletionEntryKey, SafariShared::URLCompletionEntry, SafariShared::URLCompletionEntryKeyExtractor, SafariShared::URLCompletionEntryHash, SafariShared::URLCompletionEntryValueTraits, SafariShared::URLCompletionEntryKeyTraits, WTF::FastMalloc>=\"m_table\"^{URLCompletionEntry}}\"_extras\"{unordered_map<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>, std::hash<NSString *>, std::equal_to<NSString *>, std::allocator<std::pair<NSString *const, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>>>=\"__table_\"{__hash_table<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, std::__unordered_map_hasher<NSString *, std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, std::hash<NSString *>, std::equal_to<NSString *>>, std::__unordered_map_equal<NSString *, std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, std::equal_to<NSString *>, std::hash<NSString *>>, std::allocator<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>>>=\"__bucket_list_\"{unique_ptr<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> *[], std::__bucket_list_deallocator<std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> *>>>=\"__ptr_\"{__compressed_pair<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> **, std::__bucket_list_deallocator<std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> *>>>=\"__value_\"^^v\"__value_\"{__bucket_list_deallocator<std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> *>>=\"__data_\"{__compressed_pair<unsigned long, std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> *>>=\"__value_\"Q}}}}\"__p1_\"{__compressed_pair<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *>, std::allocator<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *>>>=\"__value_\"{__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *>=\"__next_\"^v}}\"__p2_\"{__compressed_pair<unsigned long, std::__unordered_map_hasher<NSString *, std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, std::hash<NSString *>, std::equal_to<NSString *>>>=\"__value_\"Q}\"__p3_\"{__compressed_pair<float, std::__unordered_map_equal<NSString *, std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, std::equal_to<NSString *>, std::hash<NSString *>>>=\"__value_\"f}}}}"
+ "\u00a0"
- "!KeyTraits::isDeletedValue(key)"
- "!isHashTraitsEmptyValue<KeyTraits>(key)"
- "8621.9.1.10.1"
- "CanGoBack"
- "ClockSkew"
- "FailingURL"
- "NumberOfDaysInvalid"
- "WarningCategory"
- "_compareTabMatch:otherTabMatch:"
- "_distanceFromSelectedTabForTabMatch:"
- "checkKey"
- "void WTF::HashTable<OpaqueFormAutoFillFrame *, WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>>, WTF::DefaultHash<OpaqueFormAutoFillFrame *>, WTF::HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>::KeyValuePairTraits, WTF::HashTraits<OpaqueFormAutoFillFrame *>, WTF::ShouldValidateKey::Yes>::checkKey(const T &) [Key = OpaqueFormAutoFillFrame *, Value = WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>, Extractor = WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>>, HashFunctions = WTF::DefaultHash<OpaqueFormAutoFillFrame *>, Traits = WTF::HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>::KeyValuePairTraits, KeyTraits = WTF::HashTraits<OpaqueFormAutoFillFrame *>, shouldValidateKey = WTF::ShouldValidateKey::Yes, HashTranslator = WTF::HashMapTranslator<WTF::HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>::KeyValuePairTraits, WTF::DefaultHash<OpaqueFormAutoFillFrame *>>, T = OpaqueFormAutoFillFrame *]"
- "void WTF::HashTable<OpaqueFormAutoFillFrame *, WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>>, WTF::DefaultHash<OpaqueFormAutoFillFrame *>, WTF::HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>::KeyValuePairTraits, WTF::HashTraits<OpaqueFormAutoFillFrame *>, WTF::ShouldValidateKey::Yes>::checkKey(const T &) [Key = OpaqueFormAutoFillFrame *, Value = WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>, Extractor = WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>>, HashFunctions = WTF::DefaultHash<OpaqueFormAutoFillFrame *>, Traits = WTF::HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>::KeyValuePairTraits, KeyTraits = WTF::HashTraits<OpaqueFormAutoFillFrame *>, shouldValidateKey = WTF::ShouldValidateKey::Yes, HashTranslator = WTF::IdentityHashTranslator<WTF::HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>::KeyValuePairTraits, WTF::DefaultHash<OpaqueFormAutoFillFrame *>>, T = OpaqueFormAutoFillFrame *]"
- "void WTF::HashTable<OpaqueJSContext *, WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>>, WTF::DefaultHash<OpaqueJSContext *>, WTF::HashMap<OpaqueJSContext *, OpaqueJSWeakObjectMap *>::KeyValuePairTraits, WTF::HashTraits<OpaqueJSContext *>, WTF::ShouldValidateKey::Yes>::checkKey(const T &) [Key = OpaqueJSContext *, Value = WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>, Extractor = WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>>, HashFunctions = WTF::DefaultHash<OpaqueJSContext *>, Traits = WTF::HashMap<OpaqueJSContext *, OpaqueJSWeakObjectMap *>::KeyValuePairTraits, KeyTraits = WTF::HashTraits<OpaqueJSContext *>, shouldValidateKey = WTF::ShouldValidateKey::Yes, HashTranslator = WTF::HashMapTranslator<WTF::HashMap<OpaqueJSContext *, OpaqueJSWeakObjectMap *>::KeyValuePairTraits, WTF::DefaultHash<OpaqueJSContext *>>, T = OpaqueJSContext *]"
- "void WTF::HashTable<OpaqueJSContext *, WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>>, WTF::DefaultHash<OpaqueJSContext *>, WTF::HashMap<OpaqueJSContext *, OpaqueJSWeakObjectMap *>::KeyValuePairTraits, WTF::HashTraits<OpaqueJSContext *>, WTF::ShouldValidateKey::Yes>::checkKey(const T &) [Key = OpaqueJSContext *, Value = WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>, Extractor = WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueJSContext *, OpaqueJSWeakObjectMap *>>, HashFunctions = WTF::DefaultHash<OpaqueJSContext *>, Traits = WTF::HashMap<OpaqueJSContext *, OpaqueJSWeakObjectMap *>::KeyValuePairTraits, KeyTraits = WTF::HashTraits<OpaqueJSContext *>, shouldValidateKey = WTF::ShouldValidateKey::Yes, HashTranslator = WTF::IdentityHashTranslator<WTF::HashMap<OpaqueJSContext *, OpaqueJSWeakObjectMap *>::KeyValuePairTraits, WTF::DefaultHash<OpaqueJSContext *>>, T = OpaqueJSContext *]"
- "{HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>, WTF::DefaultHash<OpaqueFormAutoFillFrame *>, WTF::HashTraits<OpaqueFormAutoFillFrame *>, WTF::HashTraits<std::unique_ptr<SafariShared::FrameMetadata>>, WTF::HashTableTraits, WTF::ShouldValidateKey::Yes>=\"m_impl\"{HashTable<OpaqueFormAutoFillFrame *, WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>>, WTF::DefaultHash<OpaqueFormAutoFillFrame *>, WTF::HashMap<OpaqueFormAutoFillFrame *, std::unique_ptr<SafariShared::FrameMetadata>>::KeyValuePairTraits, WTF::HashTraits<OpaqueFormAutoFillFrame *>, WTF::ShouldValidateKey::Yes>=\"\"(?=\"m_table\"^v\"m_tableForLLDB\"^I)}}"
- "{URLCompletionEntryMap=\"_map\"{HashTable<SafariShared::URLCompletionEntryKey, SafariShared::URLCompletionEntry, SafariShared::URLCompletionEntryKeyExtractor, SafariShared::URLCompletionEntryHash, SafariShared::URLCompletionEntryValueTraits, SafariShared::URLCompletionEntryKeyTraits, WTF::ShouldValidateKey::Yes>=\"\"(?=\"m_table\"^{URLCompletionEntry}\"m_tableForLLDB\"^I)}\"_extras\"{unordered_map<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>, std::hash<NSString *>, std::equal_to<NSString *>, std::allocator<std::pair<NSString *const, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>>>=\"__table_\"{__hash_table<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, std::__unordered_map_hasher<NSString *, std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, std::hash<NSString *>, std::equal_to<NSString *>>, std::__unordered_map_equal<NSString *, std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, std::equal_to<NSString *>, std::hash<NSString *>>, std::allocator<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>>>=\"__bucket_list_\"{unique_ptr<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> *[], std::__bucket_list_deallocator<std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> *>>>=\"__ptr_\"{__compressed_pair<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> **, std::__bucket_list_deallocator<std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> *>>>=\"__value_\"^^v\"__value_\"{__bucket_list_deallocator<std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> *>>=\"__data_\"{__compressed_pair<unsigned long, std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *> *>>=\"__value_\"Q}}}}\"__p1_\"{__compressed_pair<std::__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *>, std::allocator<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *>>>=\"__value_\"{__hash_node_base<std::__hash_node<std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, void *> *>=\"__next_\"^v}}\"__p2_\"{__compressed_pair<unsigned long, std::__unordered_map_hasher<NSString *, std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, std::hash<NSString *>, std::equal_to<NSString *>>>=\"__value_\"Q}\"__p3_\"{__compressed_pair<float, std::__unordered_map_equal<NSString *, std::__hash_value_type<NSString *, std::unique_ptr<SafariShared::URLCompletionEntryExtras>>, std::equal_to<NSString *>, std::hash<NSString *>>>=\"__value_\"f}}}}"
```
