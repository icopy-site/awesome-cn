<div class="github-widget" data-repo="michaelbrusegard/awesome-wezterm"></div>
<!-- lint ignore awesome-git-repo-age -->

## Awesome WezTerm [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="https://raw.githubusercontent.com/wez/wezterm/main/assets/icon/wezterm-icon.svg" align="right" width="144" />

> Collections of awesome WezTerm plugins. [Plugin Guide](https://github.com/wezterm/wezterm/blob/main/docs/config/plugins.md). Found something cool? Please [contribute](https://github.com/michaelbrusegard/awesome-wezterm/blob/master/CONTRIBUTING.md)!

[WezTerm](https://wezfurlong.org/wezterm/) is a powerful cross-platform terminal emulator and multiplexer written by [@wez](https://github.com/wez) and implemented in [Rust](https://www.rust-lang.org).

To enhance your WezTerm configuration experience:

- [DrKJeff16/wezterm-types](https://github.com/DrKJeff16/wezterm-types) - WezTerm type annotations that can be added as a completion source in your editor to provide code assistance when working with WezTerm's Lua API. Includes community plugins support.



## AI

- [Michal1993r/ai-helper.wezterm](https://github.com/Michal1993r/ai-helper.wezterm/tree/master) - Ask AI for CLI help with LM Studio or Google Gemini.
- [dimao/ai-commander.wezterm](https://github.com/dimao/ai-commander.wezterm) - Generate and select bash commands based on natural language prompts.
- [EdenGibson/wezterm-quota-limit](https://github.com/EdenGibson/wezterm-quota-limit) - Shows Claude API usage quota in the status bar with color-coded thresholds and automatic token refresh.
- [Eric162/wezterm-agent-deck](https://github.com/Eric162/wezterm-agent-deck) - Monitors AI coding agents, shows status dots in tabs and notifications when agents need attention.
- [M-Marbouh/agent-quota.wezterm](https://github.com/M-Marbouh/agent-quota.wezterm) - Shows Claude and Codex quota usage in the status bar with reset countdowns, process-aware states, and shared caching.

## Keybinding

- [MLFlexer/modal.wezterm](https://github.com/MLFlexer/modal.wezterm) - Predefined Vim-like modal keybindings with a good looking UI.
- [sravioli/chord.wz](https://github.com/sravioli/chord.wz) - Vim-style key notation, modal key tables, and hint bars.
- [sei40kr/wez-pain-control](https://github.com/sei40kr/wez-pain-control?tab=readme-ov-file) - Pane control keybindings like tmux-pain-control.
- [sei40kr/wez-tmux](https://github.com/sei40kr/wez-tmux) - Ported tmux keybindings.
- [selectnull/pinned-tabs.wezterm](https://github.com/selectnull/pinned-tabs.wezterm) - Lets you assign a key binding to a specific tab.
- [abidibo/wezterm-cmdpicker](https://github.com/abidibo/wezterm-cmdpicker) - Add a command-palette-style fuzzy picker for keybindings. Press a trigger key to search and execute any keybinding — user-defined, config, or WezTerm defaults.
- [annie444/sync-panes.wez](https://github.com/annie444/sync-panes.wez) - Mirrors your keystrokes to every pane in the active tab — the equivalent of tmux's `synchronize-panes`.

## Media

- [xarvex/presentation.wez](https://github.com/xarvex/presentation.wez) - Rather simple presentation mode toggle.

## Neovim

- [mrjones2014/smart-splits.nvim](https://github.com/mrjones2014/smart-splits.nvim) - Provides an addon for seamless pane navigation between Neovim and the WezTerm MUX.
- [winter-again/wezterm-config.nvim](https://github.com/winter-again/wezterm-config.nvim) - Interact with the WezTerm configuration directly from Neovim.

## Panes

- [ChrisGVE/pivot_panes.wezterm](https://github.com/ChrisGVE/pivot_panes.wezterm) - Toggle pane orientation between horizontal and vertical splits.
- [bad-noodles/stack.wez](https://github.com/bad-noodles/stack.wez) - Stacked pane mode, work with multiple panes but see only one at a time.

## Session

- [DavidRR-F/quick_domains.wezterm](https://github.com/DavidRR-F/quick_domains.wezterm) - Faster way to search and attach to (SSH) domains.
- [isseii10/workspace-picker.wezterm](https://github.com/isseii10/workspace-picker.wezterm) - Workspace switcher with `zoxide` integration.
- [JuanraCM/wsinit.wezterm](https://github.com/JuanraCM/wsinit.wezterm) - A simple and flexible way to manage and initialize workspace configurations.
- [mikkasendke/sessionizer.wezterm](https://github.com/mikkasendke/sessionizer.wezterm) - Opening Git repositories as their own WezTerm workspaces using `fd`.
- [MLFlexer/resurrect.wezterm](https://github.com/MLFlexer/resurrect.wezterm) - Save and restore the state of windows, tabs and panes.
- [MLFlexer/smart_workspace_switcher.wezterm](https://github.com/MLFlexer/smart_workspace_switcher.wezterm) - Switch between workspaces with fuzzy finding and `zoxide`.
- [vieitesss/workspacesionizer.wezterm](https://github.com/vieitesss/workspacesionizer.wezterm) - Blazingly fast workspace chooser inspired by `tmux-sessionizer`.
- [abidibo/wezterm-sessions](https://github.com/abidibo/wezterm-sessions) - Save and restore sessions.
- [srackham/tabsets.wezterm](https://github.com/srackham/tabsets.wezterm) - Load, save, rename and delete named sets of tabs.
- [ryanmsnyder/workspace-manager.wezterm](https://github.com/ryanmsnyder/workspace-manager.wezterm) - Navigate projects effortlessly with smart workspace switching and keyboard-driven navigation.

## Tab bar

- [adriankarlen/bar.wezterm](https://github.com/adriankarlen/bar.wezterm) - A configurable tab bar with batteries included.
- [michaelbrusegard/tabline.wez](https://github.com/michaelbrusegard/tabline.wez) - A versatile and easy to use retro tab bar with the `lualine.nvim` configuration format.
- [rootiest/battery.wez](https://github.com/rootiest/battery.wez) - A colorful and fancy battery component for the retro tab bar.
- [yriveiro/wezterm-status](https://github.com/yriveiro/wezterm-status) - Configurable status for the retro tab bar.
- [yriveiro/wezterm-tabs](https://github.com/yriveiro/wezterm-tabs) - Configurable tabs for the retro tab bar.
- [pro-vi/wezterm-attention](https://github.com/pro-vi/wezterm-attention) - Turns your tab bar into a notification system with colored tab indicators.

## Themes

- [neapsix/wezterm](https://github.com/neapsix/wezterm) - Rosé Pine theme, all natural pine, faux fur and a bit of soho vibes.
- [sravioli/kanagawa.wz](https://github.com/sravioli/kanagawa.wz) - Kanagawa.nvim color schemes with Wave, Dragon, and Lotus variants.
- [koh-sh/wezterm-theme-rotator](https://github.com/koh-sh/wezterm-theme-rotator) - Cycle through built-in themes using keyboard shortcuts.
- [willytop8/Wezterm-Window-Tint](https://github.com/willytop8/Wezterm-Window-Tint) - Color the window frame, tab bar, and status badge by the active pane's Git root.

## Utility

- [aureolebigben/wezterm-cmd-sender](https://github.com/aureolebigben/wezterm-cmd-sender) - Send commands to multiple panes.
- [ChrisGVE/dev.wezterm](https://github.com/ChrisGVE/dev.wezterm) - Location resolver for development and deployment of a plugin.
- [ChrisGVE/lib.wezterm](https://github.com/ChrisGVE/lib.wezterm) - A library of common utility functions for plugin developers.
- [ChrisGVE/listeners.wezterm](https://github.com/ChrisGVE/listeners.wezterm) - Enables enhanced event listener capabilities with persistent state management.
- [dfsramos/wezterm-sync](https://github.com/dfsramos/wezterm-sync) - Sync your config across machines via a private GitHub Gist, with zero external dependencies.
- [lilaqua/tunicodes](https://gitlab.com/lilaqua/tunicodes) - Insert Unicode characters via their codepoints.
- [zsh-sage/toggle_terminal.wez](https://github.com/zsh-sage/toggle_terminal.wez) - An easy-to-use toggleable terminal window.
- [quantonganh/quickselect.wezterm](https://github.com/quantonganh/quickselect.wezterm) - Jump to the build error by opening them in Helix.
- [sravioli/lantern.wz](https://github.com/sravioli/lantern.wz) - Selector framework for colorschemes, fonts, GPU adapters, window appearance, and custom config presets.
- [sravioli/log.wz](https://github.com/sravioli/log.wz) - Tagged logging library with pluggable sinks and severity thresholds.
- [sravioli/memo.wz](https://github.com/sravioli/memo.wz) - Memoization, caching, and persistent state management.
- [sravioli/ribbon.wz](https://github.com/sravioli/ribbon.wz) - Builds styled text segments for status bars, tab titles, and selector previews.
- [sravioli/sigil.wz](https://github.com/sravioli/sigil.wz) - Icon and identity-color registry for processes, tools, and UI labels.
- [sravioli/warp.wz](https://github.com/sravioli/warp.wz) - General-purpose utility library with string, table, list, path, and filesystem helpers.
- [btrachey/wezterm-replay](https://github.com/btrachey/wezterm-replay) - Parse command output and get URLs, shell commands, etc. pasted into your next prompt.
- [usrivastava92/widgets.wez](https://github.com/usrivastava92/widgets.wez) - Cross-platform status bar widgets for CPU, RAM, battery, network, and disk on macOS, Linux, and Windows.
