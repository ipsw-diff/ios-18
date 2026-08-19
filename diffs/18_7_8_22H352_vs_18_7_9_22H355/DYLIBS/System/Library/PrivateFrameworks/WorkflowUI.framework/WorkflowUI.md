## WorkflowUI

> `/System/Library/PrivateFrameworks/WorkflowUI.framework/WorkflowUI`

```diff

-3612.0.1.3.0
-  __TEXT.__text: 0x2a9318
+3612.0.1.5.0
+  __TEXT.__text: 0x2a93a8
   __TEXT.__auth_stubs: 0x6240
   __TEXT.__objc_methlist: 0xc33c
   __TEXT.__const: 0x187b8
   __TEXT.__dlopen_cstrs: 0x22e
-  __TEXT.__cstring: 0xf64d
+  __TEXT.__cstring: 0xf65d
   __TEXT.__constg_swiftt: 0x97a0
   __TEXT.__swift5_typeref: 0x2719a
   __TEXT.__swift5_reflstr: 0x5673

   __TEXT.__swift5_mpenum: 0x258
   __TEXT.__gcc_except_tab: 0xc38
   __TEXT.__ustring: 0x30c
-  __TEXT.__unwind_info: 0xab88
+  __TEXT.__unwind_info: 0xab80
   __TEXT.__eh_frame: 0x629c
   __TEXT.__objc_classname: 0x203e
-  __TEXT.__objc_methname: 0x1fae8
-  __TEXT.__objc_methtype: 0x7389
-  __TEXT.__objc_stubs: 0x11cc0
+  __TEXT.__objc_methname: 0x1fb43
+  __TEXT.__objc_methtype: 0x738f
+  __TEXT.__objc_stubs: 0x11ce0
   __DATA_CONST.__got: 0x2690
   __DATA_CONST.__const: 0x2180
   __DATA_CONST.__objc_classlist: 0x910
   __DATA_CONST.__objc_catlist: 0x100
   __DATA_CONST.__objc_protolist: 0x558
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7ac8
+  __DATA_CONST.__objc_selrefs: 0x7ad0
   __DATA_CONST.__objc_protorefs: 0x1d8
   __DATA_CONST.__objc_superrefs: 0x440
   __DATA_CONST.__objc_arraydata: 0x1d0

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 18002
-  Symbols:   13686
-  CStrings:  7842
+  Symbols:   13687
+  CStrings:  7843
 
Symbols:
+ -[WFLibraryRunCoordinator openWorkflowReferenceAndRun:fromSource:withInput:state:requestOutput:runViewSource:xCallbackURLSuccessURLScheme:completionHandler:]
+ -[WFLibraryRunCoordinator runWorkflowReference:fromSource:withInput:requestOutput:runViewSource:xCallbackURLSuccessURLScheme:completionHandler:]
+ _objc_msgSend$openWorkflowReferenceAndRun:fromSource:withInput:state:requestOutput:runViewSource:xCallbackURLSuccessURLScheme:completionHandler:
+ _objc_msgSend$setXCallbackURLSuccessURLScheme:
- -[WFLibraryRunCoordinator openWorkflowReferenceAndRun:fromSource:withInput:state:requestOutput:runViewSource:completionHandler:]
- -[WFLibraryRunCoordinator runWorkflowReference:fromSource:withInput:requestOutput:runViewSource:completionHandler:]
- _objc_msgSend$openWorkflowReferenceAndRun:fromSource:withInput:state:requestOutput:runViewSource:completionHandler:
Functions:
~ _OUTLINED_FUNCTION_111 -> _OUTLINED_FUNCTION_48 : 28 -> 32
~ _OUTLINED_FUNCTION_111 : 24 -> 28
~ sub_22c90a17c -> _OUTLINED_FUNCTION_111 : 1500 -> 24
~ sub_22c90a758 -> sub_22c90619c : 104 -> 1500
~ sub_22c90a7c0 -> sub_22c906778 : 80 -> 104
~ _OUTLINED_FUNCTION_18 -> sub_22c9067e0 : 20 -> 80
~ _OUTLINED_FUNCTION_18 : 36 -> 20
~ _OUTLINED_FUNCTION_18 : 20 -> 36
~ _OUTLINED_FUNCTION_18 : 28 -> 20
~ _OUTLINED_FUNCTION_18 : 20 -> 28
~ _OUTLINED_FUNCTION_18 : 24 -> 20
~ _OUTLINED_FUNCTION_18 : 28 -> 24
~ _OUTLINED_FUNCTION_18 : 24 -> 28
~ _OUTLINED_FUNCTION_45 -> _OUTLINED_FUNCTION_18 : 20 -> 24
~ _OUTLINED_FUNCTION_18 -> _OUTLINED_FUNCTION_45 : 24 -> 20
~ _OUTLINED_FUNCTION_18 : 32 -> 24
~ _OUTLINED_FUNCTION_18 : 64 -> 32
~ _OUTLINED_FUNCTION_18 : 20 -> 64
~ _OUTLINED_FUNCTION_18 : 24 -> 20
~ _OUTLINED_FUNCTION_18 : 12 -> 24
~ _OUTLINED_FUNCTION_18 : 24 -> 12
~ _OUTLINED_FUNCTION_18 : 44 -> 24
~ _OUTLINED_FUNCTION_18 : 20 -> 44
~ _OUTLINED_FUNCTION_18 : 28 -> 20
~ _OUTLINED_FUNCTION_74 -> _OUTLINED_FUNCTION_18 : 32 -> 28
~ _OUTLINED_FUNCTION_74 : 16 -> 32
~ _OUTLINED_FUNCTION_74 : 24 -> 16
~ sub_22c90aa90 -> _OUTLINED_FUNCTION_74 : 88 -> 24
~ _OUTLINED_FUNCTION_117 -> sub_22c906ab0 : 12 -> 88
~ _OUTLINED_FUNCTION_117 : 28 -> 12
~ sub_22c90ab10 -> _OUTLINED_FUNCTION_117 : 572 -> 28
~ _OUTLINED_FUNCTION_47 -> sub_22c906b30 : 48 -> 572
~ _OUTLINED_FUNCTION_47 : 32 -> 48
~ _OUTLINED_FUNCTION_47 : 24 -> 32
~ _OUTLINED_FUNCTION_47 : 20 -> 24
~ _OUTLINED_FUNCTION_47 : 24 -> 20
~ _OUTLINED_FUNCTION_47 : 28 -> 24
~ _OUTLINED_FUNCTION_47 : 12 -> 28
~ _OUTLINED_FUNCTION_47 : 32 -> 12
~ sub_22c952bf0 -> sub_22c94ebf0 : 28 -> 36
~ sub_22c968414 -> sub_22c96441c : 212 -> 232
~ sub_22c9684e8 -> sub_22c964504 : 268 -> 332
~ sub_22c96fb3c -> sub_22c96bb98 : 44 -> 52
~ sub_22c97f134 -> sub_22c97b198 : 604 -> 612
~ sub_22c98da84 -> sub_22c989af0 : 988 -> 984
~ sub_22c98df58 -> sub_22c989fc0 : 1016 -> 1012
~ sub_22c98e350 -> sub_22c98a3b4 : 1240 -> 1236
~ sub_22c9ea56c -> sub_22c9e65cc : 5816 -> 5812
~ sub_22ca8e83c -> sub_22ca8a898 : 2660 -> 2656
~ sub_22caf2b90 -> sub_22caeebe8 : 4452 -> 4448
~ sub_22cb1bce0 -> sub_22cb17d34 : 568 -> 564
~ sub_22cb2b578 -> sub_22cb275c8 : 780 -> 776
~ -[WFLibraryRunCoordinator openWorkflowReferenceAndRun:fromSource:withInput:state:requestOutput:runViewSource:completionHandler:] -> -[WFLibraryRunCoordinator openWorkflowReferenceAndRun:fromSource:withInput:state:requestOutput:runViewSource:xCallbackURLSuccessURLScheme:completionHandler:] : 412 -> 476
~ -[WFLibraryRunCoordinator runWorkflowReference:fromSource:withInput:requestOutput:runViewSource:completionHandler:] -> -[WFLibraryRunCoordinator runWorkflowReference:fromSource:withInput:requestOutput:runViewSource:xCallbackURLSuccessURLScheme:completionHandler:] : 52 -> 56
CStrings:
+ "openWorkflowReferenceAndRun:fromSource:withInput:state:requestOutput:runViewSource:xCallbackURLSuccessURLScheme:completionHandler:"
+ "runWorkflowReference:fromSource:withInput:requestOutput:runViewSource:xCallbackURLSuccessURLScheme:completionHandler:"
+ "setXCallbackURLSuccessURLScheme:"
+ "v52@?0@\"WFWorkflowReference\"8B16@\"WFContentCollection\"20@?<v@?@\"WFContentCollection\"B@\"NSError\">28@\"NSString\"36@\"NSString\"44"
+ "v68@0:8@16@24@32B40@44@52@?60"
+ "v76@0:8@16@24@32@40B48@52@60@?68"
- "openWorkflowReferenceAndRun:fromSource:withInput:state:requestOutput:runViewSource:completionHandler:"
- "runWorkflowReference:fromSource:withInput:requestOutput:runViewSource:completionHandler:"
- "v44@?0@\"WFWorkflowReference\"8B16@\"WFContentCollection\"20@?<v@?@\"WFContentCollection\"B@\"NSError\">28@\"NSString\"36"
- "v60@0:8@16@24@32B40@44@?52"
- "v68@0:8@16@24@32@40B48@52@?60"
```
