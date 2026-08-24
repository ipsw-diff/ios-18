## com.apple.driver.AppleAVE2

> `com.apple.driver.AppleAVE2`

```diff

-803.73.1.0.0
+803.73.3.0.0
   __TEXT.__const: 0x2ef60
-  __TEXT.__cstring: 0x356cd
-  __TEXT.__os_log: 0x40bec
-  __TEXT_EXEC.__text: 0x14795c
+  __TEXT.__cstring: 0x35f1c
+  __TEXT.__os_log: 0x4130e
+  __TEXT_EXEC.__text: 0x14933c
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x290
   __DATA.__common: 0x130

   __DATA_CONST.__kalloc_var: 0x1b80
   Functions: 2450
   Symbols:   0
-  CStrings:  6980
+  CStrings:  7043
 
Functions:
~ sub_fffffff008874038 -> sub_fffffff008874058 : 72 -> 496
~ __Z26AVE_CalcBufSizeOfCodedData14_E_AVE_DevType16_E_AVE_CodecTypeii12_E_ChromaFmtiibibb13_E_AVE_RCModeiii : 1260 -> 1492
~ sub_fffffff008874814 -> sub_fffffff008874ac4 : 92 -> 520
~ sub_fffffff008874f70 -> sub_fffffff0088753cc : 80 -> 708
~ sub_fffffff008875054 -> sub_fffffff008875724 : 348 -> 592
~ sub_fffffff00887556c -> sub_fffffff008875d30 : 516 -> 852
~ sub_fffffff0088757c8 -> sub_fffffff0088760dc : 148 -> 588
~ sub_fffffff008875870 -> sub_fffffff00887633c : 140 -> 900
~ sub_fffffff008875910 -> sub_fffffff0088766d4 : 76 -> 620
~ sub_fffffff008875970 -> sub_fffffff008876954 : 88 -> 480
~ sub_fffffff0088759f0 -> sub_fffffff008876b5c : 72 -> 616
~ sub_fffffff008875ae8 -> sub_fffffff008876e74 : 168 -> 404
~ sub_fffffff008875bc8 -> sub_fffffff008877040 : 36 -> 264
~ sub_fffffff008875c8c -> sub_fffffff0088771e8 : 684 -> 932
~ __Z17AVE_CHM_AppendCmdP10_S_AVE_CHM10_E_AVE_CmdjyyP14_S_AVE_TimeOutP14_S_AVE_CmdInfoP16_S_AVE_FrameInfo : 1344 -> 1348
~ __Z20AVE_Client_CheckInfoP13_S_AVE_ClientbP35AVE_SessionSettings_UserKernel_Data : 900 -> 1384
~ __Z25AVE_Client_CheckFrameInfoP13_S_AVE_ClientP16_S_AVE_FrameInfo : 1156 -> 1380
~ __ZN7AVE_HwC9SendFwCmdEP10_S_AVE_CHMPviS2_ : 1584 -> 1808
~ sub_fffffff008997b84 -> sub_fffffff008999580 : 44 -> 48
CStrings:
+ "%lld %d AVE %s: %s AVC size overflow %d %d %d %d %lld"
+ "%lld %d AVE %s: %s AVC size overflow %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s AVC size overflow %d %d %d %lld"
+ "%lld %d AVE %s: %s AVC size overflow %d %d %d %lld\n"
+ "%lld %d AVE %s: %s AVC size overflow %d %d %d %lld %lld"
+ "%lld %d AVE %s: %s AVC size overflow %d %d %d %lld %lld\n"
+ "%lld %d AVE %s: %s AVC size overflow %d %d %lld"
+ "%lld %d AVE %s: %s AVC size overflow %d %d %lld\n"
+ "%lld %d AVE %s: %s HEVC size overflow %d %d %d %d %lld"
+ "%lld %d AVE %s: %s HEVC size overflow %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s HEVC size overflow %d %d %d %lld"
+ "%lld %d AVE %s: %s HEVC size overflow %d %d %d %lld\n"
+ "%lld %d AVE %s: %s HEVC size overflow %d %d %lld"
+ "%lld %d AVE %s: %s HEVC size overflow %d %d %lld\n"
+ "%lld %d AVE %s: %s HEVC step1 overflow %d %d %d %d %d %lld"
+ "%lld %d AVE %s: %s HEVC step1 overflow %d %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s HEVC step2 overflow %d %d %d %lld %lld"
+ "%lld %d AVE %s: %s HEVC step2 overflow %d %d %d %lld %lld\n"
+ "%lld %d AVE %s: %s LRME scaled area overflow %d %d %d %d %d %lld"
+ "%lld %d AVE %s: %s LRME scaled area overflow %d %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s LRMERC scaled area overflow %d %d %d %d %d %lld"
+ "%lld %d AVE %s: %s LRMERC scaled area overflow %d %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s negative dim %d %d %d"
+ "%lld %d AVE %s: %s negative dim %d %d %d\n"
+ "%lld %d AVE %s: %s negative dim %d %d %d %d"
+ "%lld %d AVE %s: %s negative dim %d %d %d %d\n"
+ "%lld %d AVE %s: %s negative width %d %d"
+ "%lld %d AVE %s: %s negative width %d %d\n"
+ "%lld %d AVE %s: %s negative width %d %d %d"
+ "%lld %d AVE %s: %s negative width %d %d %d\n"
+ "%lld %d AVE %s: %s pixel area overflow %d %d %d %d %lld"
+ "%lld %d AVE %s: %s pixel area overflow %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s pixel area overflow %d %d %d %lld"
+ "%lld %d AVE %s: %s pixel area overflow %d %d %d %lld\n"
+ "%lld %d AVE %s: %s size overflow %d %d %d %d %d %d %d %lld"
+ "%lld %d AVE %s: %s size overflow %d %d %d %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s size overflow %d %d %d %lld"
+ "%lld %d AVE %s: %s size overflow %d %d %d %lld\n"
+ "%lld %d AVE %s: %s:%d %s | %d multipass index out of bounds %p %d %p %d %d (expected: 0)"
+ "%lld %d AVE %s: %s:%d %s | %d multipass index out of bounds %p %d %p %d %d (expected: 0)\n"
+ "%lld %d AVE %s: %s:%d %s | Enc multipass index out of bounds %p %d %p %d %d (range: [0,%d])"
+ "%lld %d AVE %s: %s:%d %s | Enc multipass index out of bounds %p %d %p %d %d (range: [0,%d])\n"
+ "%lld %d AVE %s: %s:%d %s | codecID mismatch with session %p %d %d %d %d"
+ "%lld %d AVE %s: %s:%d %s | codecID mismatch with session %p %d %d %d %d\n"
+ "%lld %d AVE %s: %s:%d %s | frame dimension out of range %p %d %d %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | frame dimension out of range %p %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s::%s:%d %s | invalid command slot %p %d %p %p %d %p %d [0, %d)"
+ "%lld %d AVE %s: %s::%s:%d %s | invalid command slot %p %d %p %p %d %p %d [0, %d)\n"
+ "0 <= fwCmdSlot && fwCmdSlot < (AVE_Cmd_Max + (((3 + 2) + 2 + 5 + (2 + 1)) * ((2) < ((63 + 1)) ? (2) : ((63 + 1)))))"
+ "20:50:21"
+ "803.73.3"
+ "AVE_CalcBufSizeOfColocated"
+ "AVE_CalcBufSizeOfCrcQPMod"
+ "AVE_CalcBufSizeOfEntropyCoding"
+ "AVE_CalcBufSizeOfLFSRef"
+ "AVE_CalcBufSizeOfLFSResult"
+ "AVE_CalcBufSizeOfLRSResult"
+ "AVE_CalcBufSizeOfMBInputCtrl"
+ "AVE_CalcBufSizeOfMBStats"
+ "AVE_CalcBufSizeOfMCTFOutput"
+ "AVE_CalcBufSizeOfSrcNeighborData"
+ "AVE_CalcBufSizeOfSrcNeighborFwData"
+ "AVE_CalcBufSizeOfSrcNeighborInfo"
+ "AVE_CalcBufSizeOfSrcNeighborPixel"
+ "Jul 21 2026"
+ "pClient->VideoParams.sSliceMap.iNum > 0 && pClient->VideoParams.sSliceMap.iNum <= ((32) < (256) ? (32) : (256))"
+ "pFrameInfo->multiPassEndPassCounter == 0"
+ "pFrameInfo->multiPassEndPassCounter >= 0 && pFrameInfo->multiPassEndPassCounter < 2"
+ "pInfo->VideoParamsDriver.codecID == pClient->eCodecType"
+ "width >= 0 && height >= 0 && iPixelProduct <= 2147483647"
- "%lld %d AVE %s: %s:%d %s | multipass is out of range %p %d %p %d %d"
- "%lld %d AVE %s: %s:%d %s | multipass is out of range %p %d %p %d %d\n"
- "20:46:08"
- "803.73.1"
- "Apr 29 2026"
- "pClient->VideoParams.sSliceMap.iNum > 0"
- "pFrameInfo->multiPassEndPassCounter < 2"
```
