# Server GDExtension Change-Log

A history of all changes to [the ***server gdextension*** branch.](https://github.com/CoaguCo-Industries/GodotSteam-Server/tree/gdextension){ target="\_blank" }

---

## Version 4.0.1

- Changed: how initialization functions work, passing empty string now uses default IP (expected behavior)
- Fixed: incorrect verbal message from `serverInitEx()`

## Version 4.0

- Added: missing server functions from steam_gameserver.h
- Added: missing enums for server modes
- Added: in-editor documentation
- Changed: various improvements under-the-hood
- Changed: reorganized some constants
- Removed: unused enums, signals, functions
- Removed: unnecessary classes that are not part of the server build