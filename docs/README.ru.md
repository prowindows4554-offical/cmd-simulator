<div align="center">

🌐 Язык: [English](https://github.com/prowindows4554-offical/cmd-simulator?tab=readme-ov-file) · [Français](README.fr.md) · [Português](README.pt.md) · [Қазақша](README.kk.md) · **Русский**

# 💻 Симулятор CMD Windows

<img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Лицензия-MIT-green?style=for-the-badge" />

**Реалистичный симулятор командной строки Windows (cmd.exe) прямо в браузере**

[🚀 Открыть демо](https://prowindows4554-offical.github.io/cmd-simulator) · [🐛 Сообщить об ошибке](https://github.com/prowindows4554-offical/cmd-simulator/issues) · [✨ Предложить функцию](https://github.com/prowindows4554-offical/cmd-simulator/issues)

</div>

-----

## ✨ Возможности

- 🖥️ **Pixel-perfect интерфейс** — точная копия `cmd.exe` из Windows 10
- 📁 **Виртуальная файловая система** — полное дерево каталогов `C:\Users\User\...`
- ⌨️ **50+ команд** — от `dir` и `cd` до `systeminfo`, `ping`, `tracert` и `tasklist`
- 🕹️ **История команд** — навигация стрелками ↑↓
- 🔤 **Автодополнение Tab** — как в настоящем терминале
- 🎨 **Команда `color`** — смена цвета фона и текста (16 вариантов)
- 🪟 **Управление окном** — перетаскивание, разворот, свёртывание, закрытие
- 📦 **Без зависимостей** — один файл, никаких библиотек

-----

## 🚀 Быстрый старт

### Вариант 1 — Открыть онлайн

Просто перейдите по ссылке: **<https://prowindows4554-offical.github.io/cmd-simulator>**

### Вариант 2 — Запустить локально

```bash
git clone https://github.com/prowindows4554-offical/cmd-simulator.git
cd cmd-simulator
# Просто откройте index.html в браузере!
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

-----

## 📋 Поддерживаемые команды

<details>
<summary><b>📂 Файлы и директории</b> (нажмите чтобы раскрыть)</summary>

|Команда           |Описание                 |
|------------------|-------------------------|
|`dir [путь]`      |Список файлов и папок    |
|`cd [путь]`       |Сменить директорию       |
|`mkdir [имя]`     |Создать директорию       |
|`rmdir [имя]`     |Удалить директорию       |
|`del [файл]`      |Удалить файл             |
|`copy [src] [dst]`|Копировать файл          |
|`move [src] [dst]`|Переместить файл         |
|`ren [src] [dst]` |Переименовать файл       |
|`type [файл]`     |Показать содержимое файла|
|`tree [путь]`     |Дерево директорий        |

</details>

<details>
<summary><b>🖥️ Система</b></summary>

|Команда           |Описание                             |
|------------------|-------------------------------------|
|`ver`             |Версия Windows                       |
|`systeminfo`      |Подробная информация о системе       |
|`tasklist`        |Список запущенных процессов          |
|`chkdsk`          |Проверка диска                       |
|`sfc`             |Проверка целостности системных файлов|
|`shutdown /s`     |Выключение                           |
|`whoami`          |Текущий пользователь                 |
|`hostname`        |Имя компьютера                       |
|`set [переменная]`|Переменные среды                     |
|`date` / `time`   |Дата и время                         |

</details>

<details>
<summary><b>🌐 Сеть</b></summary>

|Команда          |Описание            |
|-----------------|--------------------|
|`ping [хост]`    |Пинг хоста          |
|`ipconfig`       |Сетевые настройки   |
|`netstat`        |Активные соединения |
|`tracert [хост]` |Трассировка маршрута|
|`nslookup [хост]`|DNS-запрос          |
|`arp`            |Таблица ARP         |
|`net user`       |Пользователи системы|

</details>

<details>
<summary><b>🎨 Терминал</b></summary>

|Команда            |Описание                            |
|-------------------|------------------------------------|
|`cls`              |Очистить экран                      |
|`echo [текст]`     |Вывод текста                        |
|`color [код]`      |Изменить цвета (например `color 0A`)|
|`title [заголовок]`|Заголовок окна                      |
|`prompt [строка]`  |Изменить строку приглашения         |
|`help`             |Список всех команд                  |
|`exit`             |Закрыть терминал                    |

</details>

-----

## 📁 Структура проекта

```
cmd-simulator/
│
├── index.html       # Весь симулятор — один файл
├── README.md        # Документация (English)
├── LICENSE          # MIT лицензия
├── CHANGELOG.md     # История версий
├── .gitignore       # Правила Git ignore
└── docs/
    ├── README.fr.md # Документация (Français)
    ├── README.pt.md # Документация (Português)
    ├── README.kk.md # Документация (Қазақша)
    └── README.ru.md # Документация (Русский)
```

-----

## 🛠️ Технологии

Намеренно написан **без фреймворков и зависимостей** — только чистый HTML, CSS и JavaScript:

- ⚡ Мгновенная загрузка
- 📦 Размер ~25 КБ
- 🔒 Никаких внешних запросов
- 💡 Легко читать и модифицировать

-----

## 🤝 Участие в разработке

Вклад в проект приветствуется! Вот как это сделать:

1. **Fork** репозитория
1. Создайте ветку: `git checkout -b feature/новая-команда`
1. Закоммитьте изменения: `git commit -m 'Добавить команду'`
1. Запушьте: `git push origin feature/новая-команда`
1. Откройте **Pull Request**

-----

## 📋 История изменений

См. [CHANGELOG](../CHANGELOG.md) для истории версий.

-----

## 📄 Лицензия

Распространяется под лицензией **MIT**. Подробности в файле [LICENSE](../LICENSE).

-----

<div align="center">

Сделано с ❤️ командой [ProWin Team](https://github.com/prowindows4554-offical) | Поставьте ⭐ если понравилось!

</div>
