## CoreServices

> `/System/Library/Frameworks/CoreServices.framework/CoreServices`

```diff

-1378.19.5.0.0
-  __TEXT.__text: 0x19a360
+1378.19.6.0.0
+  __TEXT.__text: 0x19a5d4
   __TEXT.__auth_stubs: 0x3210
   __TEXT.__objc_methlist: 0xc3ec
   __TEXT.__const: 0x920
-  __TEXT.__cstring: 0x20950
-  __TEXT.__oslogstring: 0x13136
-  __TEXT.__gcc_except_tab: 0x245d0
+  __TEXT.__cstring: 0x20994
+  __TEXT.__oslogstring: 0x131dc
+  __TEXT.__gcc_except_tab: 0x24620
   __TEXT.__ustring: 0x23c
-  __TEXT.__unwind_info: 0xa580
+  __TEXT.__unwind_info: 0xa598
   __TEXT.__eh_frame: 0x60
   __TEXT.__objc_classname: 0x1d52
   __TEXT.__objc_methname: 0x1be4b

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 8270
-  Symbols:   14534
-  CStrings:  10040
+  Functions: 8271
+  Symbols:   14535
+  CStrings:  10042
 
Symbols:
+ ___54-[_LSDOpenClient openAppLink:state:completionHandler:]_block_invoke_2
Functions:
~ +[LSAppLink(Internal) _appLinksWithState:context:limit:error:] : 708 -> 696
~ +[LSAppLink(Private) URLComponentsAreValidForAppLinks:error:] : 556 -> 568
~ -[_LSDOpenClient openAppLink:state:completionHandler:] : 972 -> 992
~ ___54-[_LSDOpenClient openAppLink:state:completionHandler:]_block_invoke : 24 -> 244
+ ___54-[_LSDOpenClient openAppLink:state:completionHandler:]_block_invoke_2
CStrings:
+ "-[_LSDOpenClient openAppLink:state:completionHandler:]_block_invoke"
+ "error opening app link %{private}@ is being swallowed for pid %d because it cannot map the LS database. Error was %@. It will be replaced by one that is less useful."
```
