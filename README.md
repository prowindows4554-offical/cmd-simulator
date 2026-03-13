<div align="center">

# 💻 Windows CMD Simulator

<img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />

**A realistic Windows Command Prompt (cmd.exe) simulator running directly in your browser**

[🚀 Live Demo](https://prowindows4554-offical.github.io/cmd-simulator) · [🐛 Report a Bug](https://github.com/prowindows4554-offical/cmd-simulator/issues) · [✨ Request a Feature](https://github.com/prowindows4554-offical/cmd-simulator/issues)

</div>

-----

## ✨ Features

- 🖥️ **Pixel-perfect UI** — accurate recreation of the `cmd.exe` interface from Windows 10
- 📁 **Virtual file system** — full directory tree `C:\Users\User\...`
- ⌨️ **50+ commands** — from `dir` and `cd` to `systeminfo`, `ping`, `tracert` and `tasklist`
- 🕹️ **Command history** — navigate with ↑↓ arrow keys
- 🔤 **Tab autocomplete** — just like the real terminal
- 🎨 **`color` command** — change background and text color (16 options)
- 🪟 **Window controls** — drag, maximize, minimize, close
- 📦 **Zero dependencies** — single file, no libraries needed

-----

## 🚀 Quick Start

### Option 1 — Open Online

Just visit: **<https://prowindows4554-offical.github.io/cmd-simulator>**

### Option 2 — Run Locally

```bash
git clone https://github.com/prowindows4554-offical/cmd-simulator.git
cd cmd-simulator
# Just open index.html in your browser!
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

-----

## 📋 Supported Commands

<details>
<summary><b>📂 Files & Directories</b> (click to expand)</summary>

|Command           |Description           |
|------------------|----------------------|
|`dir [path]`      |List files and folders|
|`cd [path]`       |Change directory      |
|`mkdir [name]`    |Create a directory    |
|`rmdir [name]`    |Remove a directory    |
|`del [file]`      |Delete a file         |
|`copy [src] [dst]`|Copy a file           |
|`move [src] [dst]`|Move a file           |
|`ren [src] [dst]` |Rename a file         |
|`type [file]`     |Show file contents    |
|`tree [path]`     |Display directory tree|

</details>

<details>
<summary><b>🖥️ System</b></summary>

|Command         |Description                |
|----------------|---------------------------|
|`ver`           |Windows version            |
|`systeminfo`    |Detailed system information|
|`tasklist`      |List running processes     |
|`chkdsk`        |Check disk integrity       |
|`sfc`           |System file checker        |
|`shutdown /s`   |Shut down                  |
|`whoami`        |Current user               |
|`hostname`      |Computer name              |
|`set [variable]`|Environment variables      |
|`date` / `time` |Show date and time         |

</details>

<details>
<summary><b>🌐 Network</b></summary>

|Command          |Description          |
|-----------------|---------------------|
|`ping [host]`    |Ping a host          |
|`ipconfig`       |Network configuration|
|`netstat`        |Active connections   |
|`tracert [host]` |Trace route          |
|`nslookup [host]`|DNS lookup           |
|`arp`            |ARP table            |
|`net user`       |System users         |

</details>

<details>
<summary><b>🎨 Terminal</b></summary>

|Command        |Description                    |
|---------------|-------------------------------|
|`cls`          |Clear the screen               |
|`echo [text]`  |Print text                     |
|`color [code]` |Change colors (e.g. `color 0A`)|
|`title [text]` |Set window title               |
|`prompt [text]`|Change prompt string           |
|`help`         |List all commands              |
|`exit`         |Close terminal                 |

</details>

-----

## 🎨 Color Command

Format: `color [background][text]` — each character from `0` to `F`

```
0 = Black          8 = Dark Gray
1 = Dark Blue      9 = Blue
2 = Dark Green     A = Green
3 = Dark Cyan      B = Cyan
4 = Dark Red       C = Red
5 = Dark Magenta   D = Magenta
6 = Dark Yellow    E = Yellow
7 = Gray           F = White
```

Example: `color 0A` — green text on black background (Matrix style 🟩)

-----

## 📁 Project Structure

```
cmd-simulator/
│
├── index.html       # The entire simulator — one file
├── README.md        # Documentation
├── LICENSE          # MIT License
├── CHANGELOG.md     # Version history
└── .gitignore       # Git ignore rules
```

-----

## 🛠️ Tech Stack

Built intentionally **without any frameworks or dependencies** — pure HTML, CSS and JavaScript:

- ⚡ Instant loading
- 📦 Size ~25 KB
- 🔒 No external requests
- 💡 Easy to read and modify

-----

## 🤝 Contributing

Contributions are welcome! Here’s how:

1. **Fork** the repository
1. Create a branch: `git checkout -b feature/new-command`
1. Commit your changes: `git commit -m 'Add some command'`
1. Push to the branch: `git push origin feature/new-command`
1. Open a **Pull Request**

### Ideas for improvement

- [ ] `edit` command — file editor inside the terminal
- [ ] Full `find` command syntax
- [ ] Batch file `.bat` support
- [ ] Mobile keyboard support
- [ ] Custom themes

-----

## 📄 License

Distributed under the **MIT License**. See <LICENSE> for details.

-----

<div align="center">

Made with ❤️ by [ProWin Team](https://github.com/prowindows4554-offical) | Give a ⭐ if you like it!

</div>