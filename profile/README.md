# jiji-wm

A scrollable-tiling Wayland compositor and its ecosystem of companion tools, built
around **Activities**: named, switchable desktop contexts that each own their own
ordered set of workspaces and windows — plus bookmarks, viewport paging, and an
IPC surface designed for external tooling.

## Projects

| Repo | What it is |
|------|------------|
| [**jiji**](https://github.com/jiji-wm/jiji) | The compositor. Scrollable tiling with KDE-style Activities, bookmarks, viewport paging. GPL-3.0-or-later. |
| [**jiji-activities**](https://github.com/jiji-wm/jiji-activities) | CLI for switching activities, assigning workspaces, and the fuzzy picker. |
| [**jiji-do**](https://github.com/jiji-wm/jiji-do) | Helix-style command launcher — one fuzzel menu over every capability-enabled verb. |
| [**jiji-firefox-workspaces**](https://github.com/jiji-wm/jiji-firefox-workspaces) | Native-messaging host that restores Firefox windows to their workspaces across restarts. |
| [**jiji-hamster**](https://github.com/jiji-wm/jiji-hamster) | Fork of the GNOME Hamster time tracker with block-based fact continuation and reporting. |
| [**jiji-hamster-bridge**](https://github.com/jiji-wm/jiji-hamster-bridge) | Daemon bridging activity/workspace focus to Hamster time tracking. |
| [**jiji-kbd-indicator**](https://github.com/jiji-wm/jiji-kbd-indicator) | Daemon coloring the focus ring by keyboard state — caps lock, layout, remote-window blends. |
| [**jiji-waybar**](https://github.com/jiji-wm/jiji-waybar) | Waybar fork with activity-aware workspace, window, and activities modules. MIT (tracks upstream Waybar). |
| [**jiji-workspace**](https://github.com/jiji-wm/jiji-workspace) | The development workspace — cross-repo docs, build/install scripts, and the multi-agent loop tooling the projects are built with. |

Bug reports and questions for any of these belong on the respective repo's issue tracker.

## Credits

The jiji compositor began as a fork of [niri](https://github.com/niri-wm/niri) by Ivan
Molodetskikh ([@YaLTeR](https://github.com/YaLTeR)) and its contributors, and periodically
rebases on it — the scrollable-tiling core is their excellent work, gratefully acknowledged.
jiji has since diverged into an independent project with its own identity (`jiji` binary,
`$JIJI_SOCKET`, `~/.config/jiji/`), IPC surface, and tooling; it is not a drop-in niri
replacement, and niri-ecosystem tools need porting to work with it.
