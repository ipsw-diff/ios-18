## AudioToolboxCore

> `/System/Library/PrivateFrameworks/AudioToolboxCore.framework/AudioToolboxCore`

```diff

-1456.707.1.0.0
-  __TEXT.__text: 0x308594
+1456.707.3.0.0
+  __TEXT.__text: 0x308b78
   __TEXT.__auth_stubs: 0x38b0
   __TEXT.__objc_methlist: 0x3604
   __TEXT.__const: 0x225bd
   __TEXT.__dlopen_cstrs: 0x50a
-  __TEXT.__gcc_except_tab: 0x25e98
-  __TEXT.__cstring: 0x1b882
-  __TEXT.__oslogstring: 0x13ba3
+  __TEXT.__gcc_except_tab: 0x25ed0
+  __TEXT.__cstring: 0x1b89e
+  __TEXT.__oslogstring: 0x13c83
   __TEXT.__dof_AudioTool: 0x4f1
   __TEXT.__dof_AUHosting: 0x23c
   __TEXT.__dof_AudioConv: 0x129e
   __TEXT.__dof_AUHostin0: 0x4a9
   __TEXT.__dof_IPCAudioU: 0x582
-  __TEXT.__unwind_info: 0xd488
+  __TEXT.__unwind_info: 0xd490
   __TEXT.__eh_frame: 0x88
   __TEXT.__objc_classname: 0x773
   __TEXT.__objc_methname: 0x712f

   __DATA_CONST.__objc_superrefs: 0x170
   __DATA_CONST.__objc_arraydata: 0x68
   __AUTH_CONST.__auth_got: 0x1c70
-  __AUTH_CONST.__const: 0x1a178
-  __AUTH_CONST.__cfstring: 0x7c40
+  __AUTH_CONST.__const: 0x1a1a0
+  __AUTH_CONST.__cfstring: 0x7c60
   __AUTH_CONST.__objc_const: 0x5d70
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__objc_intobj: 0x30

   __AUTH.__thread_bss: 0x18
   __DATA.__objc_ivar: 0x498
   __DATA.__data: 0xa18
-  __DATA.__bss: 0x25910
+  __DATA.__bss: 0x25900
   __DATA_DIRTY.__objc_data: 0x1040
   __DATA_DIRTY.__data: 0x124
-  __DATA_DIRTY.__bss: 0x2e0
+  __DATA_DIRTY.__bss: 0x2f0
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/Accelerate.framework/Accelerate
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 11067
+  Functions: 11068
   Symbols:   18565
-  CStrings:  8015
+  CStrings:  8019
 
Symbols:
+ GCC_except_table11583
+ GCC_except_table11590
+ GCC_except_table11601
+ GCC_except_table11604
+ GCC_except_table11607
+ GCC_except_table11611
+ GCC_except_table11617
+ __XGetProcessActiveTime
- GCC_except_table11582
- GCC_except_table11588
- GCC_except_table11600
- GCC_except_table11603
- GCC_except_table11605
- GCC_except_table11608
- GCC_except_table11616
- __ZZN20APComponent_InterApp17GetLastActiveTimeEvE11activeTimes
Functions:
~ _AudioComponentGetLastActiveTime : 256 -> 664
~ __ZNSt3__117__call_once_proxyB8ne190102INS_5tupleIJOZN12CADeprecated10TSingletonI14IPCAURegistrarE8instanceEvEUlvE_EEEEEvPv : 632 -> 1004
~ __ZN13WAVEAudioFile11ReadPacketsEhPjP28AudioStreamPacketDescriptionxS0_Pv : 804 -> 924
~ __ZN13WAVEAudioFile14ParseAudioFileEv : 7388 -> 7656
~ __ZN15WAVEAudioFormat3NewEv : 272 -> 268
+ __XGetProcessActiveTime
CStrings:
+ "%25s:%-5d  Invalid wChannels or wBitsPerSample"
+ "%25s:%-5d  ReadPackets: packet count too large"
+ "%25s:%-5d  WAVEAudioFile: wBlockAlign %u does not match expected %u (%u channels * %u bits/8); ignoring wBlockAlign"
+ "%25s:%-5d  wBitsPerSample is not a multiple of 8"
+ "com.apple.coreaudio.private"
- "%25s:%-5d  Invalid block alignment"
```
