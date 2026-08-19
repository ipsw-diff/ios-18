## com.apple.kernel

> `com.apple.kernel`

```diff

-11417.140.69.706.9
+11417.140.69.706.24
   __TEXT.__const: 0x349f0
   __TEXT.__copyio_vectors: 0xf0
-  __TEXT.__cstring: 0x6e2e5
+  __TEXT.__cstring: 0x6e2bd
   __TEXT.__os_log: 0x2a645
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0

   __DATA_CONST.__assert: 0x1cc
   __DATA_CONST.__kern_brk_desc: 0x60
   __TEXT_EXEC.__hib_text: 0xc88
-  __TEXT_EXEC.__text: 0x7e49bc
+  __TEXT_EXEC.__text: 0x7e4aec
   __KLD.__text: 0x16d4
   __PPLTEXT.__text: 0x1c930
   __PPLTRAMP.__text: 0xc008
Functions:
~ _mount_common : 5496 -> 5528
~ sub_fffffff008004204 -> sub_fffffff008004224 : 664 -> 640
~ _ip6_do_fragmentation : 1416 -> 1460
~ _sosetoptlock : 4352 -> 4372
~ sub_fffffff00836aa20 -> sub_fffffff00836aa68 : 496 -> 540
~ sub_fffffff00836ac10 -> sub_fffffff00836ac84 : 320 -> 360
~ sub_fffffff0083aeb38 -> sub_fffffff0083aebd4 : 944 -> 972
~ _kr_txfinalize : 1216 -> 1208
~ sub_fffffff0083b0068 -> sub_fffffff0083b0118 : 900 -> 892
~ sub_fffffff0083b03ec -> sub_fffffff0083b0494 : 1120 -> 1112
~ sub_fffffff0083b0a20 -> sub_fffffff0083b0ac0 : 1028 -> 1020
~ sub_fffffff0083b0e24 -> sub_fffffff0083b0ebc : 692 -> 684
~ sub_fffffff0083c9f18 -> sub_fffffff0083c9fa8 : 652 -> 648
~ sub_fffffff0083d88c0 -> sub_fffffff0083d894c : 1400 -> 1408
~ sub_fffffff0083d9f64 -> sub_fffffff0083d9ff8 : 4732 -> 4736
~ sub_fffffff0083db970 -> sub_fffffff0083dba08 : 720 -> 724
~ _dp_flow_tx_process : 3084 -> 3092
~ _fsw_ring_flush : 9600 -> 9468
~ sub_fffffff0083e5864 -> sub_fffffff0083e5884 : 256 -> 284
~ sub_fffffff0083f5260 -> sub_fffffff0083f529c : 620 -> 624
~ sub_fffffff0083f72a0 -> sub_fffffff0083f72e0 : 748 -> 756
~ _nx_mon_quantum_copy_64x : 492 -> 496
~ sub_fffffff0083fe0d4 -> sub_fffffff0083fe120 : 2496 -> 2500
~ _nx_netif_compat_na_txsync : 1076 -> 1040
~ _nx_netif_host_output : 2460 -> 2468
~ sub_fffffff00840a3cc -> sub_fffffff00840a400 : 1404 -> 1412
~ _nx_netif_mbuf_to_filter_pkt_chain : 1468 -> 1484
~ sub_fffffff00840ba94 -> sub_fffffff00840bae0 : 1352 -> 1360
~ _netif_gso_tcp_segment_mbuf : 2632 -> 2640
~ _pkt_copy_from_pkt : 4368 -> 4364
~ _pkt_copy_multi_buflet_from_pkt : 1080 -> 1148
~ sub_fffffff008415e0c -> sub_fffffff008415ea8 : 5032 -> 5116
~ sub_fffffff0084171b4 -> sub_fffffff0084172a4 : 3372 -> 3444
~ sub_fffffff0084191b8 -> sub_fffffff0084192f0 : 536 -> 540
~ sub_fffffff00841a92c -> sub_fffffff00841aa68 : 596 -> 592
~ sub_fffffff00841df08 -> sub_fffffff00841e040 : 508 -> 504
~ sub_fffffff00841e278 -> sub_fffffff00841e3ac : 856 -> 852
~ _firehose_buffer_tracepoint_reserve_slow.cold.1 : 13936 -> 13632
CStrings:
+ "doff + len <= (uint32_t)mbuf_maxlen(m)"
- "((intptr_t)dp - (intptr_t)mbuf_datastart(m)) + len <= (uint32_t)mbuf_maxlen(m)"
```
