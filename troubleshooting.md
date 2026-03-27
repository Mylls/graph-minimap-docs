---
layout: default
title: Troubleshooting
---

# Troubleshooting

## The minimap does not open from the keyboard shortcut

This is usually a shortcut conflict inside Unreal Editor.

Try this:

1. Open the graph editor `Window` menu first and launch `Graph Minimap` from there.
2. If the menu works, open Unreal Editor keyboard shortcuts and rebind the minimap command.

## The minimap is not visible in a supported graph

- Make sure the plugin is enabled in `Edit > Plugins`
- Try opening it from the active graph editor `Window` menu
- Make sure the active tab is a supported graph editor

## The minimap looks too busy on large graphs

Try adjusting:

- Dense Graph Mode Node Threshold
- Focus Lens Scale
- Focus Lens Opacity
- Comment Tag visibility
- Minimum Node Size

## The plugin asks to rebuild from source

This is normal for source plugins when opening a project that has not built the plugin yet. Let Unreal compile the plugin and reopen the project if needed.

## Window size or placement looks wrong

Enable `Save Minimap Location & Size` and reopen the graph editor. If needed, resize the minimap once and let the setting persist for the next session.

