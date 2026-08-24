## safarifetcherd

> `/usr/libexec/safarifetcherd`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-7621.9.1.10.1
+7621.10.1.10.2
   __TEXT.__text: 0x9bbc
   __TEXT.__auth_stubs: 0x7f0
   __TEXT.__objc_stubs: 0x23e0
-  __TEXT.__objc_methlist: 0x1334
+  __TEXT.__objc_methlist: 0x135c
   __TEXT.__gcc_except_tab: 0xbe0
   __TEXT.__const: 0x98
-  __TEXT.__objc_methname: 0x52d7
+  __TEXT.__objc_methname: 0x5301
   __TEXT.__cstring: 0x435
   __TEXT.__objc_classname: 0x175
-  __TEXT.__objc_methtype: 0x247e
+  __TEXT.__objc_methtype: 0x2486
   __TEXT.__oslogstring: 0xfe8
   __TEXT.__dlopen_cstrs: 0x4e
   __TEXT.__unwind_info: 0x498

   __DATA_CONST.__objc_superrefs: 0x28
   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA_CONST.__objc_intobj: 0x18
-  __DATA.__objc_const: 0x15f0
-  __DATA.__objc_selrefs: 0x1128
+  __DATA.__objc_const: 0x1608
+  __DATA.__objc_selrefs: 0x1140
   __DATA.__objc_ivar: 0xf8
   __DATA.__objc_data: 0x190
   __DATA.__data: 0x368

   - /usr/lib/libobjc.A.dylib
   Functions: 262
   Symbols:   227
-  CStrings:  1006
+  CStrings:  1009
 
CStrings:
+ "_webView:didReceiveConsoleLogForTesting:"
+ "_webView:startXRSessionWithFeatures:colorFormat:depthFormat:completionHandler:"
+ "_webViewDidEnterStandbyForTesting:"
+ "_webViewDidExitStandbyForTesting:"
+ "_webViewWillEnterFullscreen:"
+ "v32@0:8@\"WKWebView\"16@\"NSString\"24"
+ "v32@0:8@\"WKWebView\"16@\"UIInputSuggestion\"24"
+ "v56@0:8@\"WKWebView\"16Q24Q32Q40@?<v@?@@\"UIViewController\">48"
+ "v56@0:8@16Q24Q32Q40@?48"
+ "webView:insertInputSuggestion:"
- "_webView:decideWebApplicationCacheQuotaForSecurityOrigin:currentQuota:totalBytesNeeded:decisionHandler:"
- "_webView:startXRSessionWithFeatures:completionHandler:"
- "_webView:updatedClientBadge:fromSecurityOrigin:"
- "v40@0:8@\"WKWebView\"16Q24@?<v@?@@\"UIViewController\">32"
- "v40@0:8@16Q24@?32"
- "v56@0:8@\"WKWebView\"16@\"WKSecurityOrigin\"24Q32Q40@?<v@?Q>48"
- "v56@0:8@16@24Q32Q40@?48"
```
