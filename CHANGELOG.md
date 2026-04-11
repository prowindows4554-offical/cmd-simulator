# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.2] - 2026-04-11

### Added

- **Language menu** — switch interface language on the fly (English, Русский, Español, Français, 中文)
- **Language support** — menu labels and command error messages change with selected language
- **.bat file support** — upload a `.bat` file via File menu, choose destination folder, execute it instantly
- `.bat` executor handles `@echo off`, `rem` comments and `::` lines correctly

## [1.0.1] - 2026-03-13

### Added

- Dropdown menus for File, Edit, View and Help
- **File** menu: Exit button
- **Edit** menu: Clear Screen option
- **View** menu: color themes (Matrix, Default, White on Blue, Black on White) and Full Screen toggle
- **GitHub** button — opens repository in a new tab directly from the menu bar
- **Help → About Command Prompt** — realistic About window in winver style with version, copyright and GitHub link

## [1.0.0] - 2026-03-13

### Added

- Initial release by ProWin Team
- 50+ supported CMD commands
- Virtual file system (`C:\Users\User\...`)
- Command history navigation with ↑↓ arrow keys
- Tab autocomplete
- Draggable window with minimize / maximize / close controls
- `color` command with 16 color combinations
- Network commands: `ping`, `ipconfig`, `netstat`, `tracert`, `nslookup`, `arp`
- System commands: `systeminfo`, `tasklist`, `chkdsk`, `sfc`, `shutdown`
- File commands: `dir`, `cd`, `mkdir`, `rmdir`, `del`, `copy`, `move`, `ren`, `type`, `tree`
- Zero dependencies — pure HTML / CSS / JS, single file