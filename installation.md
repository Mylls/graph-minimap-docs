---
layout: default
title: Installation
---

# Installation

## Requirements

- Unreal Engine 5.6.x
- A C++ project or a project that can build plugins from source

## Install Into a Project

1. Close Unreal Editor.
2. Extract the `GraphMinimap` plugin folder into your project's `Plugins` directory.
3. Reopen the project.
4. If prompted, allow Unreal to build the plugin.
5. Make sure the plugin is enabled in `Edit > Plugins`.

Expected install path:

```text
YourProject/
  Plugins/
    GraphMinimap/
```

## After Installation

Once the project opens successfully:

- Open a supported graph editor
- Use the graph editor `Window` menu and choose `Graph Minimap`
- If desired, configure the plugin in `Editor Preferences > Plugins > Graph Minimap`

## Notes

- Graph Minimap is an editor-only plugin.
- It does not affect runtime gameplay builds.
- If Unreal asks to rebuild the plugin, let it compile before testing.

