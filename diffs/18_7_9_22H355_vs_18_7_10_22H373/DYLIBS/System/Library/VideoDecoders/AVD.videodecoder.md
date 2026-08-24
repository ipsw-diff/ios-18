## AVD.videodecoder

> `/System/Library/VideoDecoders/AVD.videodecoder`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-865.0.0.0.0
-  __TEXT.__text: 0x17848c
+867.0.0.0.0
+  __TEXT.__text: 0x178f10
   __TEXT.__auth_stubs: 0xe90
   __TEXT.__const: 0xc3cb
   __TEXT.__gcc_except_tab: 0x9ec
-  __TEXT.__oslogstring: 0xfb9e
+  __TEXT.__oslogstring: 0xfbd8
   __TEXT.__cstring: 0x5f71
-  __TEXT.__unwind_info: 0x1c10
+  __TEXT.__unwind_info: 0x1c18
   __DATA_CONST.__got: 0x340
   __DATA_CONST.__const: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 2502
-  Symbols:   3309
-  CStrings:  1929
+  Functions: 2503
+  Symbols:   3310
+  CStrings:  1930
 
Symbols:
+ __ZN15CAVDHevcDecoder16createRefPicListEP28hevc_picture_parameter_set_tP22hevc_slice_info_structP15HevcPictureInfo
+ __ZN17CAVDMvHevcDecoder16createRefPicListEP28hevc_picture_parameter_set_tP22hevc_slice_info_structP15HevcPictureInfo
+ __ZN6CAHDec21workUnitOffsetInvalidEjjP22hevc_slice_info_struct
- __ZN15CAVDHevcDecoder16createRefPicListEP28hevc_picture_parameter_set_tP15hevc_slice_infoP15HevcPictureInfo
- __ZN17CAVDMvHevcDecoder16createRefPicListEP28hevc_picture_parameter_set_tP15hevc_slice_infoP15HevcPictureInfo
Functions:
~ __ZN15CAVDHevcDecoder13DecodePictureEjjb : 368 -> 372
- __ZN15CAVDHevcDecoder16createRefPicListEP28hevc_picture_parameter_set_tP15hevc_slice_infoP15HevcPictureInfo
~ __ZN16CAHDecCatnipHevc15populateAvdWorkEj : 4112 -> 4292
~ __ZN14CAHDecRoseHevc15populateAvdWorkEj : 3004 -> 3080
~ __ZN15CAHDecTansyHevc15populateAvdWorkEj : 4112 -> 4292
~ __ZN17CAVDMvHevcDecoder13DecodePictureEjjb : 368 -> 372
~ __ZN16CAHDecCloverHevc15populateAvdWorkEj : 3312 -> 3440
~ __ZN15CAHDecClaryHevc15populateAvdWorkEj : 4112 -> 4292
~ __ZN15CAHDecLotusHevc15populateAvdWorkEj : 3312 -> 3440
~ __ZN15CAHDecIxoraHevc15populateAvdWorkEj : 4120 -> 4300
~ __ZN15CAHDecDaisyHevc15populateAvdWorkEj : 4120 -> 4300
~ __ZN15CAHDecViolaHevc15populateAvdWorkEj : 3312 -> 3440
~ __ZN16CAHDecDahliaHevc15populateAvdWorkEj : 4120 -> 4300
+ __ZN6CAHDec21workUnitOffsetInvalidEjjP22hevc_slice_info_struct
+ __ZN15CAVDHevcDecoder16createRefPicListEP28hevc_picture_parameter_set_tP22hevc_slice_info_structP15HevcPictureInfo
~ __ZN16CAHDecSalviaHevc15populateAvdWorkEj : 3312 -> 3440
~ __ZN16CAHDecBorageHevc15populateAvdWorkEj : 4112 -> 4292
~ __ZN18CAHDecHibiscusHevc15populateAvdWorkEj : 4120 -> 4300
~ __ZN16CAHDecKopsiaHevc15populateAvdWorkEj : 4120 -> 4300
~ __ZN15CAHDecThymeHevc15populateAvdWorkEj : 4112 -> 4292
CStrings:
+ "20:47:09"
+ "20:47:10"
+ "AppleAVD: ERROR: workUnits %d exceeded max %d on slice %d"
+ "Jul 21 2026"
- "20:42:56"
- "20:42:57"
- "Apr 29 2026"
```
