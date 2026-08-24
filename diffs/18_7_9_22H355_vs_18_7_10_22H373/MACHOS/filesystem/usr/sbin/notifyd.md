## notifyd

> `/usr/sbin/notifyd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-342.0.0.0.0
-  __TEXT.__text: 0xb4f8
-  __TEXT.__auth_stubs: 0x960
-  __TEXT.__const: 0x1b0
-  __TEXT.__cstring: 0x1bf5
-  __DATA_CONST.__auth_got: 0x4b0
+342.0.0.700.1
+  __TEXT.__text: 0xb4d4
+  __TEXT.__auth_stubs: 0x970
+  __TEXT.__const: 0x1b8
+  __TEXT.__cstring: 0x1c23
+  __DATA_CONST.__auth_got: 0x4b8
   __DATA_CONST.__got: 0x78
   __DATA_CONST.__const: 0xb30
   __DATA.__data: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   Functions: 135
-  Symbols:   168
-  CStrings:  284
+  Symbols:   169
+  CStrings:  285
 
Symbols:
+ ___memset_chk
Functions:
~ sub_1000037b0 : 308 -> 316
~ sub_100004040 -> sub_100004048 : 1492 -> 1428
~ sub_100005eb8 -> sub_100005e80 : 828 -> 848
CStrings:
+ "_path_vnode_create_node"
+ "_path_vnode_create_nodes"
+ "pnode->plen <= sizeof(buf)"
- "_path_node_update"
- "buf != NULL"
```
