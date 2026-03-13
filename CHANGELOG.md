# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] - 2026-03-13

### Added

- Dropdown menus for File, Edit, View, GitHub and Help
- **File** menu: Exit button
- **Edit** menu: Clear Screen option
- **View** menu: color themes (Matrix, Default, White on Blue, Black on White), Full Screen toggle
- **GitHub** menu item — opens repository in a new tab
- **Help → About Command Prompt** — realistic About window (winver-style) with version, copyright and GitHub link
- Multilingual README support: Français, Português, Қазақша, Русский (in `docs/` folder)
- Language switcher at the top of each README

### Changed

- Year corrected to 2026 in LICENSE

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