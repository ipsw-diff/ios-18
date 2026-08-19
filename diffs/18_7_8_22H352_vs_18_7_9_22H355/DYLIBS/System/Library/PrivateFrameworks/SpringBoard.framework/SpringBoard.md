## SpringBoard

> `/System/Library/PrivateFrameworks/SpringBoard.framework/SpringBoard`

```diff

-4503.5.10.0.0
-  __TEXT.__text: 0x9bbce0
+4503.5.10.1.0
+  __TEXT.__text: 0x9bc148
   __TEXT.__auth_stubs: 0x5360
   __TEXT.__init_offsets: 0x4
-  __TEXT.__objc_methlist: 0xab248
-  __TEXT.__const: 0x12c00
-  __TEXT.__oslogstring: 0x59533
-  __TEXT.__cstring: 0x76460
+  __TEXT.__objc_methlist: 0xab298
+  __TEXT.__const: 0x12c10
+  __TEXT.__oslogstring: 0x595fc
+  __TEXT.__cstring: 0x7649f
   __TEXT.__gcc_except_tab: 0x1529c
   __TEXT.__ustring: 0xcb4
   __TEXT.__dlopen_cstrs: 0x313
-  __TEXT.__unwind_info: 0x288a0
+  __TEXT.__unwind_info: 0x288b0
   __TEXT.__eh_frame: 0xc98
-  __TEXT.__objc_classname: 0x20034
-  __TEXT.__objc_methname: 0x1aff28
+  __TEXT.__objc_classname: 0x20052
+  __TEXT.__objc_methname: 0x1b003e
   __TEXT.__objc_methtype: 0x46e36
-  __TEXT.__objc_stubs: 0xe4840
-  __DATA_CONST.__got: 0x9b78
+  __TEXT.__objc_stubs: 0xe4900
+  __DATA_CONST.__got: 0x9b80
   __DATA_CONST.__const: 0x1ad40
-  __DATA_CONST.__objc_classlist: 0x4db0
+  __DATA_CONST.__objc_classlist: 0x4db8
   __DATA_CONST.__objc_catlist: 0x338
   __DATA_CONST.__objc_nlcatlist: 0x8
   __DATA_CONST.__objc_protolist: 0x2708
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x45eb8
+  __DATA_CONST.__objc_selrefs: 0x45ee8
   __DATA_CONST.__objc_protorefs: 0xb8
   __DATA_CONST.__objc_superrefs: 0x3be8
   __DATA_CONST.__objc_arraydata: 0x1678
   __AUTH_CONST.__auth_got: 0x29c8
   __AUTH_CONST.__const: 0xf588
-  __AUTH_CONST.__cfstring: 0x6b180
-  __AUTH_CONST.__objc_const: 0x23d070
+  __AUTH_CONST.__cfstring: 0x6b1a0
+  __AUTH_CONST.__objc_const: 0x23d190
   __AUTH_CONST.__objc_arrayobj: 0x15f0
   __AUTH_CONST.__objc_doubleobj: 0x570
   __AUTH_CONST.__objc_intobj: 0x2928
   __AUTH_CONST.__objc_dictobj: 0x2f8
-  __AUTH.__objc_data: 0xe830
-  __DATA.__objc_ivar: 0xe354
+  __AUTH.__objc_data: 0xe880
+  __DATA.__objc_ivar: 0xe360
   __DATA.__data: 0x1e8b0
   __DATA.__crash_info: 0x40
   __DATA.__bss: 0xad8

   - /usr/lib/libsp.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libutil.dylib
-  Functions: 65049
-  Symbols:   137289
-  CStrings:  82215
+  Functions: 65057
+  Symbols:   137313
+  CStrings:  82230
 
Symbols:
+ -[SBMainWorkspace _shouldThrottleUntrustedURLLaunchForApplication:options:]
+ -[SBMainWorkspace _untrustedURLLaunchRequestWindowEntryForBundleID:atTime:]
+ -[SBURLLaunchRequestWindowEntry requestCount]
+ -[SBURLLaunchRequestWindowEntry setRequestCount:]
+ -[SBURLLaunchRequestWindowEntry setWindowStart:]
+ -[SBURLLaunchRequestWindowEntry windowStart]
+ GCC_except_table180
+ GCC_except_table182
+ _OBJC_CLASS_$_SBURLLaunchRequestWindowEntry
+ _OBJC_IVAR_$_SBMainWorkspace._untrustedURLLaunchRequestWindowEntries
+ _OBJC_IVAR_$_SBURLLaunchRequestWindowEntry._requestCount
+ _OBJC_IVAR_$_SBURLLaunchRequestWindowEntry._windowStart
+ _OBJC_METACLASS_$_SBURLLaunchRequestWindowEntry
+ _SBWorkspaceHasApplicationSceneInLockedEnvironmentLayoutStateMatchingApplication
+ __OBJC_$_INSTANCE_METHODS_SBURLLaunchRequestWindowEntry
+ __OBJC_$_INSTANCE_VARIABLES_SBURLLaunchRequestWindowEntry
+ __OBJC_$_PROP_LIST_SBURLLaunchRequestWindowEntry
+ __OBJC_CLASS_RO_$_SBURLLaunchRequestWindowEntry
+ __OBJC_METACLASS_RO_$_SBURLLaunchRequestWindowEntry
+ _objc_msgSend$_shouldThrottleUntrustedURLLaunchForApplication:options:
+ _objc_msgSend$_untrustedURLLaunchRequestWindowEntryForBundleID:atTime:
+ _objc_msgSend$requestCount
+ _objc_msgSend$setRequestCount:
+ _objc_msgSend$setWindowStart:
+ _objc_msgSend$windowStart
- GCC_except_table183
CStrings:
+ "Application %@ has exceeded the URL scheme request rate limit."
+ "SBURLLaunchRequestWindowEntry"
+ "TQ,N,V_requestCount"
+ "Td,N,V_windowStart"
+ "Throttled untrusted URL request from %{public}@"
+ "Untrusted user action request from %{public}@ to %{public}@ (url: %{public}@): isUILocked=%d, sceneVisible=%d, viewService=%d, bgEntitled=%d, allowed=%d"
+ "_requestCount"
+ "_shouldThrottleUntrustedURLLaunchForApplication:options:"
+ "_untrustedURLLaunchRequestWindowEntries"
+ "_untrustedURLLaunchRequestWindowEntryForBundleID:atTime:"
+ "_windowStart"
+ "requestCount"
+ "setRequestCount:"
+ "setWindowStart:"
+ "windowStart"
```
