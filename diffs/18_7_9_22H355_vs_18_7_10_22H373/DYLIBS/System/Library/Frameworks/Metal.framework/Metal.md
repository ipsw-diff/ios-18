## Metal

> `/System/Library/Frameworks/Metal.framework/Metal`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-368.51.0.0.0
-  __TEXT.__text: 0x193110
+368.53.0.0.0
+  __TEXT.__text: 0x193254
   __TEXT.__auth_stubs: 0x1bb0
   __TEXT.__objc_methlist: 0x175ac
   __TEXT.__gcc_except_tab: 0x9188

   __TEXT.__oslogstring: 0x16a0
   __TEXT.__ustring: 0x1be
   __TEXT.text_env: 0x2568
-  __TEXT.__unwind_info: 0x6a10
+  __TEXT.__unwind_info: 0x6a18
   __TEXT.__eh_frame: 0x78
   __TEXT.__objc_classname: 0x30e7
   __TEXT.__objc_methname: 0x2cf49
Functions:
~ __ZN25MTLMetalScriptBuilderImpl13resetInternalEb : 188 -> 268
~ __ZN25MTLMetalScriptBuilderImpl18addComputePipelineEP28MTLComputePipelineDescriptor : 612 -> 664
~ __ZN25MTLMetalScriptBuilderImpl17addRenderPipelineEP27MTLRenderPipelineDescriptor : 900 -> 964
~ __ZN25MTLMetalScriptBuilderImpl21addMeshRenderPipelineEP31MTLMeshRenderPipelineDescriptor : 1144 -> 1220
~ __ZN25MTLMetalScriptBuilderImpl21addTileRenderPipelineEP31MTLTileRenderPipelineDescriptor : 612 -> 664
CStrings:
+ "19:57:51"
+ "Jul  6 2026"
+ "Jul  6 2026 19:57:51"
- "19:57:06"
- "Jul 20 2025"
- "Jul 20 2025 19:57:06"
```
