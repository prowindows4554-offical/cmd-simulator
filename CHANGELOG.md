# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2026-04-21

### Added

- **Notepad** — fully realistic Notepad window with all menus (File, Edit, Format, View, Help)
- Notepad **keyboard shortcuts**: Ctrl+S, Ctrl+N, Ctrl+O, Ctrl+D, Ctrl+Z, Ctrl+A, Ctrl+F, Ctrl+H, Ctrl+G
- Notepad **Download** button (Ctrl+D) — download file directly to device
- Notepad **Save / Save As** — saves files to virtual file system
- Notepad **Find & Replace** — search and replace text
- Notepad **Go To line** — jump to any line number
- Notepad **status bar** — shows line/column and character count
- Notepad **mobile toolbar** — tap buttons for Save, Download, Undo, Find, Close
- **`download`** command — download file from virtual FS; download folder as ZIP archive
- **`upload`** command — import real files into virtual file system with custom name/destination
- **`mount`** command — mount a file or folder as a new virtual drive (e.g. `mount Z:\ myfolder`)
- **Alt+Enter** — toggle fullscreen mode for CMD window
- **Auto fullscreen** on page load (CMD window opens maximized automatically)
- **Mobile adaptation** — CMD auto-fills screen on mobile devices
- **Mobile keyboard toolbar** — Ctrl, Alt, Shift, Esc, Tab, arrow keys, Enter, Backspace, CLS

### Changed

- About window: version updated to 1.1.0

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

- Initial release by prowindows4554
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