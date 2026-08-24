## com.apple.kernel

> `com.apple.kernel`

```diff

-11417.140.69.706.24
+11417.140.69.706.66
   __TEXT.__const: 0x349f0
   __TEXT.__copyio_vectors: 0xf0
-  __TEXT.__cstring: 0x6e2bd
-  __TEXT.__os_log: 0x2a645
+  __TEXT.__cstring: 0x6e37c
+  __TEXT.__os_log: 0x2a8ef
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__mod_init_func: 0x2d0
-  __DATA_CONST.__const: 0xe2760
+  __DATA_CONST.__const: 0xe2800
   __DATA_CONST.__hib_const: 0x120
   __DATA_CONST.__kalloc_type: 0x13400
   __DATA_CONST.__kalloc_var: 0x7a30
   __DATA_CONST.__assert: 0x1cc
   __DATA_CONST.__kern_brk_desc: 0x60
   __TEXT_EXEC.__hib_text: 0xc88
-  __TEXT_EXEC.__text: 0x7e4aec
+  __TEXT_EXEC.__text: 0x7e5bcc
   __KLD.__text: 0x16d4
   __PPLTEXT.__text: 0x1c930
   __PPLTRAMP.__text: 0xc008

   __DATA.__data: 0x17b81
   __DATA.__lock_grp: 0x54e8
   __DATA.__percpu: 0x3a40
-  __DATA.__common: 0x58050
-  __DATA.__bss: 0x30530
+  __DATA.__common: 0x58070
+  __DATA.__bss: 0x30868
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init_entry_set: 0x10de8
+  __BOOTDATA.__init_entry_set: 0x10e18
   __BOOTDATA.__init: 0x56f10
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x46722
-  Functions: 19447
+  Functions: 19453
   Symbols:   0
-  CStrings:  17143
+  CStrings:  17162
 
CStrings:
+ "%s: bpf%u already attached to %s error %d"
+ "%s: bpf%u and bpf%u have incompatible flags 0x%x != 0x%x error %d"
+ "%s: bpf%u and bpf%u have incompatible interfaces %s and %s error %d"
+ "%s: d_from buffers not allocated error %d"
+ "%s: d_from is closing or detached error %d"
+ "%s: d_to is closing or detaching error %d"
+ "%s: downgrade JIT for entry [%p, %p)"
+ "%s: interface %s not supported error %d"
+ "%s: necp_session_add_domain_trie total_mem_size mismatch (%u vs %zu)\n"
+ "1111111111122221111111112"
+ "B16@?0^{task={lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}{os_refcnt=AI}BBBBIIQ^{_vm_map}{queue_entry=^{queue_entry}^{queue_entry}}^{task_watchports}^v{queue_entry=^{queue_entry}^{queue_entry}}^{restartable_ranges}^{processor_set}^{affinity_space}iIiiissiQ{recount_task=^{recount_track}^{recount_usage}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}[4^{ipc_port}]^{ipc_port}[14{exception_action=^{ipc_port}iiii^{label}}]{hardened_exception_action={exception_action=^{ipc_port}iiii^{label}}II}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}[3^{ipc_port}]^^{ipc_port}^{ipc_space}^{ledger}{queue_entry=^{queue_entry}^{queue_entry}}iI^vQQCBB^Q^Q^Q^Q^Q^Q^Q^Q^QIIIIII^{proc_ro}^{kcdata_descriptor}Q{queue_entry=^{queue_entry}^{queue_entry}}^{label}IIQQIBBBBb4b4b4b4CCCCB*^{vm_shared_region}QQQ^{thread_call}{queue_entry=^{queue_entry}^{queue_entry}}ii^{bank_task}^{ipc_importance_task}{vm_extmod_statistics=qqqqqq}{task_requested_policy=b1b1b2b2b1b1b2b1b3b3b3b1b5b3b3b1b3b1b1b3b1b3b1b1b17}{task_effective_policy=b1b1b2b1b1b1b2b1b1b3b3b1b1b1b4b1b1b1b3b3b1b1b29}{task_pend_token=(?={?=b1b1b1b1b1b1b1b1b1b1b1b1b1}I)}b1b1b1b1b1b27b1b1b1b1b28^{io_stat_info}{task_writes_counters=QQQQ}{task_writes_counters=QQQQ}{_cpu_time_qos_stats=QQQQQQQ}{_cpu_time_qos_stats=QQQQQQQ}IIQCCCiii{queue_entry=^{queue_entry}^{queue_entry}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}b16b1b1b1b1b1b1b1[2^{coalition}][2{queue_entry=^{queue_entry}^{queue_entry}}]QCCCCIQ{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}iIQ[16C]Q^{_vmobject_list_output_}II^{vm_deferred_reclamation_metadata_s}Q{task_security_config=(?={?=b1b1b1}C)}}8"
+ "BIOCSETIF"
+ "BIOCSEXTHDR"
+ "BIOCSPKTHDRV2"
+ "BIOCSTRUNCATE"
+ "TRACKER - %s:%d Could not dump entries, entry tlv size %lu exceeds scratch pad size %lu\n"
+ "TRACKER - %s:%d Could not dump entry, buffer too small\n"
+ "flow_registration_count"
+ "key_parse: invalid address extension.\n"
+ "mem_entry_wimg_non_writable"
+ "necp_client.c"
+ "necp_flow_registration_count underflow @%s:%d"
+ "vm_map_copyout_internal"
+ "vm_map_remap"
- "%s: d_from is closing error %d"
- "%s: d_to is closing error %d"
- "111111111112221111111112"
- "B16@?0^{task={lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}{os_refcnt=AI}BBBBIIQ^{_vm_map}{queue_entry=^{queue_entry}^{queue_entry}}^{task_watchports}^v{queue_entry=^{queue_entry}^{queue_entry}}^{restartable_ranges}^{processor_set}^{affinity_space}iIiiissiQ{recount_task=^{recount_track}^{recount_usage}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}[4^{ipc_port}]^{ipc_port}[14{exception_action=^{ipc_port}iiii^{label}}]{hardened_exception_action={exception_action=^{ipc_port}iiii^{label}}II}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}[3^{ipc_port}]^^{ipc_port}^{ipc_space}^{ledger}{queue_entry=^{queue_entry}^{queue_entry}}iI^vQQCBB^Q^Q^Q^Q^Q^Q^Q^Q^QIIIIII^{proc_ro}^{kcdata_descriptor}Q{queue_entry=^{queue_entry}^{queue_entry}}^{label}IIQQIBBBBb4b4b4b4CCCCB*^{vm_shared_region}QQQ^{thread_call}{queue_entry=^{queue_entry}^{queue_entry}}ii^{bank_task}^{ipc_importance_task}{vm_extmod_statistics=qqqqqq}{task_requested_policy=b1b1b2b2b1b1b2b1b3b3b3b1b5b3b3b1b3b1b1b3b1b3b1b1b17}{task_effective_policy=b1b1b2b1b1b1b2b1b1b3b3b1b1b1b4b1b1b1b3b3b1b1b29}{task_pend_token=(?={?=b1b1b1b1b1b1b1b1b1b1b1b1b1}I)}b1b1b1b1b1b27b1b1b1b1b28^{io_stat_info}{task_writes_counters=QQQQ}{task_writes_counters=QQQQ}{_cpu_time_qos_stats=QQQQQQQ}{_cpu_time_qos_stats=QQQQQQQ}IIQCCCiii{queue_entry=^{queue_entry}^{queue_entry}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}b16b1b1b1b1b1b1b1[2^{coalition}][2{queue_entry=^{queue_entry}^{queue_entry}}]QCCCCIQ{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}iIQ[16C]Q^{_vmobject_list_output_}Q^{vm_deferred_reclamation_metadata_s}Q{task_security_config=(?={?=b1b1b1}C)}}8"
- "bpf_setif"
```
