## com.apple.iokit.IOTimeSyncFamily

> `com.apple.iokit.IOTimeSyncFamily`

```diff

-1340.13.0.0.0
-  __TEXT.__cstring: 0x32b0
-  __TEXT.__os_log: 0x7798
+1340.14.0.0.0
+  __TEXT.__cstring: 0x32dd
+  __TEXT.__os_log: 0x7870
   __TEXT.__const: 0x1d8
-  __TEXT_EXEC.__text: 0x31d10
+  __TEXT_EXEC.__text: 0x31dc0
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xd0
   __DATA.__common: 0x638

   __DATA_CONST.__kalloc_var: 0x280
   Functions: 1389
   Symbols:   0
-  CStrings:  632
+  CStrings:  635
 
Functions:
~ __ZN20IOTimeSyncUserClient12initWithTaskEP4taskPvjP12OSDictionary : 276 -> 364
~ __ZN32IOTimeSyncClockManagerUserClient12initWithTaskEP4taskPvjP12OSDictionary : 1236 -> 1324
CStrings:
+ "IOTimeSyncClockManagerUserClient::initWithTask: missing entitlement com.apple.private.timesync.direct-userclient\n"
+ "IOTimeSyncUserClient::initWithTask: missing entitlement com.apple.private.timesync.direct-userclient\n"
+ "com.apple.private.timesync.direct-userclient"
```
