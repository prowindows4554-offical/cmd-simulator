<div align="center">

# 💻 Windows CMD Simulator

<img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />

🌐 Langue : [English](https://github.com/prowindows4554-offical/cmd-simulator?tab=readme-ov-file) · **Français** · [Português](README.pt.md) · [Қазақша](README.kk.md) · [Русский](README.ru.md)

**Un simulateur réaliste de l’invite de commandes Windows (cmd.exe) directement dans votre navigateur**

[🚀 Démo en ligne](https://prowindows4554-offical.github.io/cmd-simulator) · [🐛 Signaler un bug](https://github.com/prowindows4554-offical/cmd-simulator/issues) · [✨ Proposer une fonctionnalité](https://github.com/prowindows4554-offical/cmd-simulator/issues)

</div>

-----

## ✨ Fonctionnalités

- 🖥️ **Interface pixel-perfect** — reproduction fidèle de `cmd.exe` sous Windows 10
- 📁 **Système de fichiers virtuel** — arborescence complète `C:\Users\User\...`
- ⌨️ **50+ commandes** — de `dir` et `cd` à `systeminfo`, `ping`, `tracert` et `tasklist`
- 🕹️ **Historique des commandes** — navigation avec les touches ↑↓
- 🔤 **Autocomplétion Tab** — comme dans le vrai terminal
- 🎨 **Commande `color`** — changer la couleur du fond et du texte (16 options)
- 🪟 **Contrôles de fenêtre** — déplacer, agrandir, réduire, fermer
- 📦 **Zéro dépendance** — un seul fichier, aucune bibliothèque

-----

## 🚀 Démarrage rapide

### Option 1 — Ouvrir en ligne

Visitez simplement : **<https://prowindows4554-offical.github.io/cmd-simulator>**

### Option 2 — Exécuter localement

```bash
git clone https://github.com/prowindows4554-offical/cmd-simulator.git
cd cmd-simulator
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

-----

## 📋 Commandes supportées

<details>
<summary><b>📂 Fichiers & Répertoires</b> (cliquer pour développer)</summary>

|Commande          |Description                     |
|------------------|--------------------------------|
|`dir [chemin]`    |Lister les fichiers et dossiers |
|`cd [chemin]`     |Changer de répertoire           |
|`mkdir [nom]`     |Créer un répertoire             |
|`rmdir [nom]`     |Supprimer un répertoire         |
|`del [fichier]`   |Supprimer un fichier            |
|`copy [src] [dst]`|Copier un fichier               |
|`move [src] [dst]`|Déplacer un fichier             |
|`ren [src] [dst]` |Renommer un fichier             |
|`type [fichier]`  |Afficher le contenu d’un fichier|
|`tree [chemin]`   |Afficher l’arborescence         |

</details>

<details>
<summary><b>🖥️ Système</b></summary>

|Commande        |Description                     |
|----------------|--------------------------------|
|`ver`           |Version de Windows              |
|`systeminfo`    |Informations système détaillées |
|`tasklist`      |Liste des processus en cours    |
|`chkdsk`        |Vérifier l’intégrité du disque  |
|`sfc`           |Vérificateur de fichiers système|
|`shutdown /s`   |Éteindre                        |
|`whoami`        |Utilisateur actuel              |
|`hostname`      |Nom de l’ordinateur             |
|`set [variable]`|Variables d’environnement       |
|`date` / `time` |Afficher la date et l’heure     |

</details>

<details>
<summary><b>🌐 Réseau</b></summary>

|Commande         |Description            |
|-----------------|-----------------------|
|`ping [hôte]`    |Pinguer un hôte        |
|`ipconfig`       |Configuration réseau   |
|`netstat`        |Connexions actives     |
|`tracert [hôte]` |Tracer la route        |
|`nslookup [hôte]`|Requête DNS            |
|`arp`            |Table ARP              |
|`net user`       |Utilisateurs du système|

</details>

<details>
<summary><b>🎨 Terminal</b></summary>

|Commande        |Description                          |
|----------------|-------------------------------------|
|`cls`           |Effacer l’écran                      |
|`echo [texte]`  |Afficher du texte                    |
|`color [code]`  |Changer les couleurs (ex. `color 0A`)|
|`title [texte]` |Définir le titre de la fenêtre       |
|`prompt [texte]`|Changer l’invite de commande         |
|`help`          |Lister toutes les commandes          |
|`exit`          |Fermer le terminal                   |

</details>

-----

## 📁 Structure du projet

```
cmd-simulator/
│
├── index.html       # Le simulateur complet — un seul fichier
├── README.md        # Documentation (English)
├── LICENSE          # Licence MIT
├── CHANGELOG.md     # Historique des versions
├── .gitignore       # Règles Git ignore
└── docs/
    ├── README.fr.md # Documentation (Français)
    ├── README.pt.md # Documentation (Português)
    ├── README.kk.md # Documentation (Қазақша)
    └── README.ru.md # Documentation (Русский)
```

-----

## 🛠️ Stack technique

Construit **sans aucun framework ni dépendance** — HTML, CSS et JavaScript purs :

- ⚡ Chargement instantané
- 📦 Taille ~25 Ko
- 🔒 Aucune requête externe
- 💡 Facile à lire et modifier

-----

## 🤝 Contribution

Les contributions sont les bienvenues ! Voici comment :

1. **Fork** le dépôt
1. Créez une branche : `git checkout -b feature/nouvelle-commande`
1. Committez vos changements : `git commit -m 'Ajouter une commande'`
1. Poussez la branche : `git push origin feature/nouvelle-commande`
1. Ouvrez une **Pull Request**

-----

## 📋 Changelog

Voir [CHANGELOG](../CHANGELOG.md) pour l’historique des versions.

-----

## 📄 Licence

Distribué sous la **licence MIT**. Voir [LICENSE](../LICENSE) pour les détails.

-----

<div align="center">

Fait avec ❤️ par [ProWin Team](https://github.com/prowindows4554-offical) | Donnez une ⭐ si vous aimez !

</div>
