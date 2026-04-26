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
- [Ghostling](https://github.com/ghostty-org/ghostling) - A minimum viable terminal emulator built on the libghostty C API in a single C file, using Raylib for rendering.
- [ghostty-opentui](https://github.com/remorses/ghostty-opentui) - A fast ANSI/VT terminal parser powered by libghostty-vt, with JSON output, plain text stripping, and a TUI viewer built on OpenTUI.
- [go-libghostty](https://github.com/mitchellh/go-libghostty) - Go bindings for libghostty-vt with cgo, static linking by default.
- [libghostty-dart](https://github.com/elias8/libghostty) - Dart FFI bindings to libghostty-vt for building terminal emulators in Flutter.
- [libghostty-rs](https://github.com/Uzaaft/libghostty-rs) - Rust FFI bindings and safe API for libghostty-vt, with a Rust port of Ghostling using macroquad.
- [libghostty-spm](https://github.com/Lakr233/libghostty-spm) - Prebuilt GhosttyKit.xcframework distributed as a Swift Package for easy integration.
- [Restty](https://github.com/wiedymi/restty) - A lightweight web terminal library powered by libghostty-vt, WebGPU, and text-shaper, with xterm.js API compatibility.
- [Zmx](https://github.com/neurosnap/zmx) - Session persistence for terminal processes, using libghostty-vt for terminal state restore.

## Terminal Apps & Clients

- [Dotty](https://github.com/codymullins/dotty) - Terminal emulator built with `.NET` + libghostty.
- [Echo](https://replay.software/echo) - A fast, modern SSH and Mosh client for iOS and iPadOS powered by Ghostty.
- [emacs-libgterm](https://github.com/rwc9u/emacs-libgterm) - Terminal emulator for Emacs using libghostty-vt, with ANSI colors, scrollback, and cursor sync via a Zig dynamic module.
- [fantastty](https://github.com/blaine/fantastty) - A macOS terminal emulator built on Ghostty's libghostty with session workspaces, notes, and live tab previews.
- [Geistty](https://github.com/daiimus/geistty) - Native iOS/iPadOS SSH terminal powered by Ghostty's terminal engine with Metal rendering and tmux control mode.
- [Ghostel](https://github.com/dakra/ghostel) - Terminal emulator for Emacs with true color, shell integration, OSC 8 hyperlinks, mouse tracking, Kitty keyboard protocol, and incremental rendering.
- [Ghostree](https://github.com/sidequery/ghostree) - A fork of Ghostty with native support for git worktree & AI agents.
- [Husk](https://github.com/dindin12138/Husk) - A lightweight, daemon-based Wayland terminal written in C++ and powered by libghostty.
- [kytos](https://github.com/jwintz/kytos) - A macOS terminal emulator built on libghostty and KelyphosKit.
- [macterm](https://github.com/thdxg/macterm) - A lightweight, native terminal for macOS built with SwiftUI and libghostty.
- [Mori](https://github.com/vaayne/mori) - A native macOS workspace terminal organized around projects and worktrees, powered by tmux and libghostty.
- [Muxy](https://github.com/muxy-app/muxy) - A macOS terminal multiplexer built with SwiftUI and libghostty.
- [OpenOwl](https://github.com/sanvibyfish/openowl-app) - A macOS native Git GUI and terminal desktop app built with Swift, libghostty, and Metal GPU rendering.
- [phantty](https://github.com/arya-s/phantty) - Windows renderer for libghostty-vt.
- [RootShell](https://github.com/kitknox/rootshell) - The terminal, reimagined for Apple platforms.
- [Spectty](https://github.com/ocnc/spectty) - A fast native SSH & Mosh terminal for iOS.
- [Umbra](https://github.com/charliesbot/umbra) - A high-performance, GPU-accelerated Android terminal powered by libghostty.
- [VVTerm](https://github.com/vivy-company/vvterm) - A Ghostty-powered SSH client for iOS, iPad, and macOS with iCloud sync and voice-to-command.
- [Watchtower](https://github.com/markhuot/watchtower) - A stacked terminal emulator with an integrated browser pane.

## Web & Embedded Terminals

- [browstty](https://github.com/Snoupix/browstty) - A Zig WASM module that implements libghostty to emulate a terminal in the browser.
- [ghostty-web](https://github.com/coder/ghostty-web) - Ghostty for the web with xterm.js API compatibility.
- [jupyterlab-ghostty-terminal](https://github.com/mvfti/jupyterlab-ghostty-terminal) - A terminal emulator extension for JupyterLab powered by libghostty.
- [mdnb](https://mdnb.app) - A native macOS markdown editor with git sync + embedded Ghostty terminal.
- [obsidian-ghostty-terminal](https://github.com/lavs9/obsidian-ghostty-terminal) - True Ghostty terminal (libghostty-vt WASM) embedded in Obsidian with multi-split support and file-explorer context menu.
- [pynb](https://pynb.app/) - A native macOS Jupyter-compatible Python notebook app with an embedded Ghostty terminal.
- [RemoteTTYs](https://github.com/finch-xu/RemoteTTYs) - Remote terminal access to your home PC/Mac from a browser using ghostty-web, with a Go agent that requires no open ports or NAT traversal.
- [vscode-bootty](https://github.com/0xBigBoss/vscode-bootty) - An alternative terminal extension for VS Code powered by libghostty-vt via WebAssembly.
- [webterm](https://github.com/rcarmo/webterm) - A web terminal server with a dashboard mode and live terminal tiles, using ghostty-web for WebAssembly-based rendering.

## AI Tools & Agent Orchestration

- [ADHDev](https://github.com/vilmire/adhdev) - Self-hosted control plane for AI coding agents with a libghostty-backed session-host runtime.
- [agtmux-term](https://github.com/g960059/agtmux-term) - AI-agent-aware terminal emulator with libghostty and a SwiftUI sidebar.
- [AiyuTerm](https://github.com/aiyu-ai/AiyuTerm) - Native macOS terminal workspace with multi-repo sidebar, persistent split layouts, SSH, tmux, and real-time AI agent status, powered by Ghostty.
- [Aizen](https://aizen.win) - Bring order to your projects, environments, and day-to-day work. A macOS workspace for parallel development.
- [cmux](https://github.com/manaflow-ai/cmux) - A Ghostty-based macOS terminal with vertical tabs and notifications for AI coding agents.
- [codelima](https://github.com/brianrackle/codelima) - Safely run coding agents in fully isolated local VM sandboxes.
- [Commander](https://commanderai.app/) - A native macOS AI workspace for coding agents with diff review, git workflow, and worktree management.
- [Factory Floor](https://github.com/alltuner/factoryfloor) - A native macOS workspace for parallel development with git worktrees, Claude Code agents, and embedded dev servers with automatic port detection.
- [frep](https://github.com/emmettlu/frep) - An agentic terminal emulator built on libghostty.
- [Mux](https://github.com/coder/mux) - Desktop and browser app for isolated, parallel agentic development.
- [Supacode](https://github.com/supabitapp/supacode) - An open-source native macOS command center for running coding agents in parallel, powered by libghostty.
- [taskers](https://github.com/OneNoted/taskers) - An agent-first terminal workspace app with a Rust shell, flexible terminal backend, and Niri-like tiling model.
- [termscope](https://github.com/mwunsch/termscope) - Headless terminal emulator CLI powered by libghostty-vt.
- [tuidoscope](https://github.com/shuv1337/tuidoscope) - A terminal multiplexer for TUI apps with tab sidebar, fuzzy command palette, session persistence, and vim-style navigation, built with OpenTUI, SolidJS, and libghostty.
- [YEN](https://yen.chat) - Terminal-first IDE with native speech-to-text, stylish themes, and custom notifications.
- [Zentty](https://github.com/dedene/zentty) - A native macOS terminal for agentic development with vertical tabs, hyprland/niri-style worklanes, notifications, and an agent-aware sidebar.

## System Integrations & Utilities

- [findr](https://github.com/FujiwaraChoki/findr) - A keyboard-driven file manager for macOS with an embedded terminal via libghostty.
- [hauntty](https://github.com/seruman/hauntty) - Terminal session persistence using Ghostty's VT parser compiled to WASM, written in Go.
- [Hot Notes](https://github.com/emadda/hot-notes) - macOS Notes fuzzy search.
- [NeoShell](https://neoshell.app/) - A shell-first remote workspace on iPad.
- [OmniWM](https://github.com/BarutSRB/OmniWM) - macOS tiling window manager inspired by Niri and Hyprland, with a Ghostty-powered quake terminal.
- [OrbStack](https://orbstack.dev/) - Fast, lightweight Docker & Linux on macOS, with a built-in Ghostty-powered terminal.
- [Ribari](https://github.com/dalvlatko/ribari-releases) - A niri-inspired tiling web browser for macOS with libghostty integration.
- [Trolley](https://github.com/weedonandscott/trolley) - A terminal emulator runtime for distributing cross-platform TUI applications to end users, powered by libghostty.
- [vanish](https://github.com/psyclyx/vanish) - A lightweight terminal session multiplexer built on libghostty-vt.

## Resources

- [libghostty API Reference](https://libghostty.tip.ghostty.org/index.html) - API reference documentation for libghostty.
- [libghostty is coming](https://mitchellh.com/writing/libghostty-is-coming) - Announcement post introducing libghostty and its direction.

## Contributing

Contributions are welcome. Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

This repository is licensed under the [MIT License](LICENSE).
