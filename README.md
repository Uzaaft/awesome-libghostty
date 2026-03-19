# Awesome libghostty

A curated list of awesome projects, tools, and resources built with or for libghostty.

## Contents

- [Core & Libraries](#core--libraries)
- [Terminal Apps & Clients](#terminal-apps--clients)
- [Web & Embedded Terminals](#web--embedded-terminals)
- [AI Tools & Agent Orchestration](#ai-tools--agent-orchestration)
- [System Integrations & Utilities](#system-integrations--utilities)
- [Resources](#resources)

## Core & Libraries

- [Ghostty](https://github.com/ghostty-org/ghostty) - Reference implementation and home of libghostty.
- [ghostty-opentui](https://github.com/remorses/ghostty-opentui) - A fast ANSI/VT terminal parser powered by libghostty-vt, with JSON output, plain text stripping, and a TUI viewer built on OpenTUI.
- [libghostty-dart](https://github.com/elias8/libghostty) - Dart FFI bindings to libghostty-vt for building terminal emulators in Flutter.
- [libghostty-spm](https://github.com/Lakr233/libghostty-spm) - Prebuilt GhosttyKit.xcframework distributed as a Swift Package for easy integration.
- [Restty](https://github.com/wiedymi/restty) - A lightweight web terminal library powered by libghostty-vt, WebGPU, and text-shaper, with xterm.js API compatibility.
- [Zmx](https://github.com/neurosnap/zmx) - Session persistence for terminal processes, using libghostty-vt for terminal state restore.

## Terminal Apps & Clients

- [Dotty](https://github.com/codymullins/dotty) - Terminal emulator built with `.NET` + libghostty.
- [Echo](https://replay.software/echo) - A fast, modern SSH and Mosh client for iOS and iPadOS powered by Ghostty.
- [emacs-libgterm](https://github.com/rwc9u/emacs-libgterm) - Terminal emulator for Emacs using libghostty-vt, with ANSI colors, scrollback, and cursor sync via a Zig dynamic module.
- [fantastty](https://github.com/blaine/fantastty) - A macOS terminal emulator built on Ghostty's libghostty with session workspaces, notes, and live tab previews
- [Ghostree](https://github.com/sidequery/ghostree) - A fork of Ghostty with native support for git worktree & AI agents.
- [Husk](https://github.com/dindin12138/Husk) - A lightweight, daemon-based Wayland terminal written in C++ and powered by libghostty.
- [kytos](https://github.com/jwintz/kytos) - A macOS terminal emulator built on libghostty and KelyphosKit.
- [OpenOwl](https://github.com/sanvibyfish/openowl-app) - A macOS native Git GUI and terminal desktop app built with Swift, libghostty, and Metal GPU rendering.
- [phantty](https://github.com/arya-s/phantty) - Windows renderer for libghostty-vt.
- [RootShell](https://github.com/kitknox/rootshell) - The terminal, reimagined for Apple platforms.
- [Spectty](https://github.com/ocnc/spectty) - A fast native SSH & Mosh terminal for iOS.
- [VVTerm](https://github.com/vivy-company/vvterm) - A Ghostty-powered SSH client for iOS, iPad, and macOS with iCloud sync and voice-to-command.
- [Umbra](https://github.com/charliesbot/umbra) - A high-performance, GPU-accelerated Android terminal powered by libghostty.
- [Watchtower](https://github.com/markhuot/watchtower) - A stacked terminal emulator with an integrated browser pane.

## Web & Embedded Terminals

- [browstty](https://github.com/Snoupix/browstty) - A Zig WASM module that implements libghostty to emulate a terminal in the browser.
- [ghostty-web](https://github.com/coder/ghostty-web) - Ghostty for the web with xterm.js API compatibility.
- [mdnb](https://mdnb.app) - A native macOS markdown editor with git sync + embedded Ghostty terminal.
- [pynb](https://pynb.app/) - A native macOS Jupyter-compatible Python notebook app with an embedded Ghostty terminal.
- [webterm](https://github.com/rcarmo/webterm) - A web terminal server with a dashboard mode and live terminal tiles, using ghostty-web for WebAssembly-based rendering.

## AI Tools & Agent Orchestration

- [cmux](https://github.com/manaflow-ai/cmux) - A Ghostty-based macOS terminal with vertical tabs and notifications for AI coding agents.
- [Commander](https://commanderai.app/) - A native macOS AI workspace for coding agents with diff review, git workflow, and worktree management.
- [Mux](https://github.com/coder/mux) - Desktop and browser app for isolated, parallel agentic development.
- [Supacode](https://github.com/supabitapp/supacode) - An open-source native macOS command center for running coding agents in parallel, powered by libghostty.
- [YEN](https://yen.chat) - Terminal-first IDE with native speech-to-text, stylish themes, and custom notifications.

## System Integrations & Utilities

- [Hot Notes](https://github.com/emadda/hot-notes) - macOS Notes fuzzy search.
- [NeoShell](https://neoshell.app/) - A shell-first remote workspace on iPad.
- [OmniWM](https://github.com/BarutSRB/OmniWM) - macOS tiling window manager inspired by Niri and Hyprland, with a Ghostty-powered quake terminal.
- [OrbStack](https://orbstack.dev/) - Fast, lightweight Docker & Linux on macOS, with a built-in Ghostty-powered terminal.
- [Trolley](https://github.com/weedonandscott/trolley) - A terminal emulator runtime for distributing cross-platform TUI applications to end users, powered by libghostty.

## Resources

- [libghostty API Reference](https://libghostty.tip.ghostty.org/index.html) - API reference documentation for libghostty.
- [libghostty is coming](https://mitchellh.com/writing/libghostty-is-coming) - Announcement post introducing libghostty and its direction.

## Contributing

Contributions are welcome. Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

This repository is licensed under the [MIT License](LICENSE).
