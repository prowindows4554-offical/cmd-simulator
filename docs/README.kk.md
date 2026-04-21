<div align="center">

🌐 Тіл: [English](https://github.com/prowindows4554-offical/cmd-simulator?tab=readme-ov-file) · [Français](README.fr.md) · [Português](README.pt.md) · **Қазақша** · [Русский](README.ru.md)

# 💻 Windows CMD Симуляторы

<img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Лицензия-MIT-green?style=for-the-badge" />

**Браузерде тікелей жұмыс істейтін Windows командалық жолының (cmd.exe) шынайы симуляторы**

[🚀 Тікелей демо](https://prowindows4554-offical.github.io/cmd-simulator) · [🐛 Қате туралы хабарлау](https://github.com/prowindows4554-offical/cmd-simulator/issues) · [💬 Талқылаулар](https://github.com/prowindows4554-offical/cmd-simulator/discussions)

</div>

-----

## ✨ Мүмкіндіктер

- 🖥️ **Пиксельдік дәлдік интерфейс** — Windows 10-дағы `cmd.exe` интерфейсінің дәл көшірмесі
- 📁 **Виртуалды файл жүйесі** — толық каталог ағашы `C:\Users\User\...`
- ⌨️ **50+ команда** — `dir` және `cd`-ден `systeminfo`, `ping`, `tracert` және `tasklist`-ке дейін
- 🕹️ **Команда тарихы** — ↑↓ пернелерімен шарлау
- 🔤 **Tab автотолтыру** — нақты терминал сияқты
- 🎨 **`color` командасы** — фон мен мәтін түсін өзгерту (16 нұсқа)
- 🪟 **Терезе басқару** — жылжыту, үлкейту, кішірейту, жабу
- 📝 **Блокнот** — сақтау, жүктеу, іздеу және пернелер тіркесімімен толық Notepad
- 📥 **`download` командасы** — файл немесе қалтаны (ZIP ретінде) жүктеп алу
- 📤 **`upload` командасы** — нақты файлдарды виртуалды файл жүйесіне импорттау
- 💾 **`mount` командасы** — файл немесе қалтаны виртуалды диск ретінде монтаждау
- 🌐 **5 тіл** — English, Русский, Español, Français, 中文
- 📱 **Мобильді нұсқа** — автоматты толық экран + пернетақта тулбары
- ⛶ **Толық экран режимі** — Alt+Enter CMD-ді толық экранға ауыстырады
- 📦 **Нөл тәуелділік** — бір файл, кітапхана қажет емес

-----

## 🚀 Жылдам бастау

### 1-нұсқа — Онлайн ашу

Тек осы мекенжайға өтіңіз: **<https://prowindows4554-offical.github.io/cmd-simulator>**

### 2-нұсқа — Жергілікті іске қосу

```bash
git clone https://github.com/prowindows4554-offical/cmd-simulator.git
cd cmd-simulator
# index.html файлын браузерде ашыңыз!
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

-----

## 📋 Қолдау көрсетілетін командалар

<details>
<summary><b>📂 Файлдар мен каталогтар</b> (кеңейту үшін басыңыз)</summary>

|Команда           |Сипаттама                      |
|------------------|-------------------------------|
|`dir [жол]`       |Файлдар мен қалталарды тізімдеу|
|`cd [жол]`        |Каталогты өзгерту              |
|`mkdir [атау]`    |Каталог жасау                  |
|`rmdir [атау]`    |Каталогты жою                  |
|`del [файл]`      |Файлды жою                     |
|`copy [src] [dst]`|Файлды көшіру                  |
|`move [src] [dst]`|Файлды жылжыту                 |
|`ren [src] [dst]` |Файлды қайта атау              |
|`type [файл]`     |Файл мазмұнын көрсету          |
|`tree [жол]`      |Каталог ағашын көрсету         |

</details>

<details>
<summary><b>🖥️ Жүйе</b></summary>

|Команда         |Сипаттама                     |
|----------------|------------------------------|
|`ver`           |Windows нұсқасы               |
|`systeminfo`    |Толық жүйе ақпараты           |
|`tasklist`      |Іске қосылған процестер тізімі|
|`chkdsk`        |Дискіні тексеру               |
|`sfc`           |Жүйелік файлдарды тексеру     |
|`shutdown /s`   |Өшіру                         |
|`whoami`        |Ағымдағы пайдаланушы          |
|`hostname`      |Компьютер атауы               |
|`set [айнымалы]`|Орта айнымалылары             |
|`date` / `time` |Күн мен уақытты көрсету       |

</details>

<details>
<summary><b>🌐 Желі</b></summary>

|Команда          |Сипаттама           |
|-----------------|--------------------|
|`ping [хост]`    |Хостты тексеру      |
|`ipconfig`       |Желі конфигурациясы |
|`netstat`        |Белсенді қосылымдар |
|`tracert [хост]` |Маршрутты бақылау   |
|`nslookup [хост]`|DNS сұрауы          |
|`arp`            |ARP кестесі         |
|`net user`       |Жүйе пайдаланушылары|

</details>

<details>
<summary><b>🎨 Терминал</b></summary>

|Команда         |Сипаттама                         |
|----------------|----------------------------------|
|`cls`           |Экранды тазалау                   |
|`echo [мәтін]`  |Мәтінді шығару                    |
|`color [код]`   |Түстерді өзгерту (мыс. `color 0A`)|
|`title [мәтін]` |Терезе тақырыбын орнату           |
|`prompt [мәтін]`|Шақыру жолын өзгерту              |
|`help`          |Барлық командалар тізімі          |
|`exit`          |Терминалды жабу                   |

</details>

-----

## 📁 Жоба құрылымы

```
cmd-simulator/
│
├── index.html       # Толық симулятор — бір файл
├── README.md        # Құжаттама (English)
├── LICENSE          # MIT Лицензиясы
├── CHANGELOG.md     # Нұсқалар тарихы
├── .gitignore       # Git ignore ережелері
└── docs/
    ├── README.fr.md # Құжаттама (Français)
    ├── README.pt.md # Құжаттама (Português)
    ├── README.kk.md # Құжаттама (Қазақша)
    └── README.ru.md # Құжаттама (Русский)
```

-----

## 🛠️ Технологиялар

Әдейі **фреймворксіз және тәуелділіксіз** жасалған — таза HTML, CSS және JavaScript:

- ⚡ Лездік жүктеу
- 📦 Өлшемі ~25 КБ
- 🔒 Сыртқы сұраулар жоқ
- 💡 Оқуға және өзгертуге оңай

-----

## 🤝 Үлес қосу

Үлестер қош келді! Қалай:

1. Репозиторийді **Fork** жасаңыз
1. Тармақ жасаңыз: `git checkout -b feature/жаңа-команда`
1. Өзгерістерді commit жасаңыз: `git commit -m 'Команда қосу'`
1. Push жасаңыз: `git push origin feature/жаңа-команда`
1. **Pull Request** ашыңыз

-----

## 📋 Өзгерістер журналы

Нұсқалар тарихы үшін [CHANGELOG](../CHANGELOG.md) қараңыз.

-----

## 📄 Лицензия

**MIT Лицензиясы** бойынша таратылады. Толығырақ [LICENSE](../LICENSE) қараңыз.

-----

<div align="center">

[prowindows4554](https://github.com/prowindows4554-offical) ❤️ жасады | Ұнаса ⭐ қойыңыз!

</div>