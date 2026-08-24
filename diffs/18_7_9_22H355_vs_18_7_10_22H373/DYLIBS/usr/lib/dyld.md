## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff
CStrings:
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Tue Jul 21 20:39:39 PDT 2026; root:libignition-56~62681/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Tue Jul 21 20:39:39 PDT 2026; root:libignition-56~62681/libignition_core/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Wed Apr 29 20:36:37 PDT 2026; root:libignition-56~62644/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Wed Apr 29 20:36:37 PDT 2026; root:libignition-56~62644/libignition_core/RELEASE_ARM64E"
```
