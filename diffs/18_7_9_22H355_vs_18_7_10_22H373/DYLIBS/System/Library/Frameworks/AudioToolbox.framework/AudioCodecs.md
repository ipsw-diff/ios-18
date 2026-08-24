## AudioCodecs

> `/System/Library/Frameworks/AudioToolbox.framework/AudioCodecs`

```diff

-746.8.7.0.0
-  __TEXT.__text: 0x599b1c
+746.8.9.0.0
+  __TEXT.__text: 0x599cfc
   __TEXT.__auth_stubs: 0x1540
   __TEXT.__const: 0x3028cc
-  __TEXT.__cstring: 0xa1fc
+  __TEXT.__cstring: 0xa244
   __TEXT.__gcc_except_tab: 0x10700
-  __TEXT.__oslogstring: 0x18275
+  __TEXT.__oslogstring: 0x183b1
   __TEXT.__ustring: 0x20
   __TEXT.__unwind_info: 0x8a30
   __TEXT.__eh_frame: 0x790

   - /usr/lib/libc++.1.dylib
   Functions: 8807
   Symbols:   15908
-  CStrings:  3066
+  CStrings:  3071
 
Functions:
~ __ZN23SBRIndividChannelStream13ResetSbrSliceERK9SBRHeaderR7SBRInfoR16SBRFrequencyBandR15SBRFreqBandDatabb : 356 -> 364
~ __ZN23SBRIndividChannelStream28ApplySpectralBandReplicationER9SBRHeaderR7SBRInfoR15SBRFreqBandData : 476 -> 480
~ __ZN16SBRFrequencyBand17CalculateSBRPatchEhjhPKhjP15PatchParametersPj : 508 -> 520
~ __ZN4apac3hoa11CodecConfig11DeserializeER16TBitstreamReaderIjE : 4292 -> 4428
~ __ZN14metadata_bsfmt23LZWCompressionProcessor10DecompressERNSt3__16vectorIhNS1_9allocatorIhEEEER16TBitstreamReaderIjEj : 1544 -> 1680
~ __ZN14metadata_bsfmt22HuffmanCodingProcessor10DecompressERNSt3__16vectorIhNS1_9allocatorIhEEEER16TBitstreamReaderIjEj : 556 -> 692
~ __ZN14SBREncodeFrame14CalculatePatchEP17SBR_CONFIGURATIONP16SBRFrequencyBand : 160 -> 208
CStrings:
+ "%25s:%-5d  Error: incorrect number of bits produced after decoding in HuffmanCodingProcessor::Decompress"
+ "%25s:%-5d  Error: incorrect number of bits produced after decoding in LZWCompressionProcessor::Decompress"
+ "%25s:%-5d  Number of channels sent in TCEs is less than core channels in hoa::CodecConfig::Deserialize()"
+ "20:54:19"
+ "CalculatePatch"
+ "Jul 14 2026"
+ "patch < 0 || patch >= kMax_SBRNumberOfPatches_Is6 "
- "20:36:47"
- "Jan 21 2026"
```
