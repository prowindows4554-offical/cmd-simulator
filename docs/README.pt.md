<div align="center">

# 💻 Windows CMD Simulator

<img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />

🌐 Idioma: [English](../README.md) · [Français](README.fr.md) · **Português** · [Қазақша](README.kk.md) · [Русский](README.ru.md)

**Um simulador realista do Prompt de Comando do Windows (cmd.exe) diretamente no seu navegador**

[🚀 Demo ao vivo](https://prowindows4554-offical.github.io/cmd-simulator) · [🐛 Reportar bug](https://github.com/prowindows4554-offical/cmd-simulator/issues) · [✨ Sugerir funcionalidade](https://github.com/prowindows4554-offical/cmd-simulator/issues)

</div>

-----

## ✨ Funcionalidades

- 🖥️ **Interface pixel-perfect** — recriação fiel do `cmd.exe` do Windows 10
- 📁 **Sistema de arquivos virtual** — árvore completa `C:\Users\User\...`
- ⌨️ **50+ comandos** — de `dir` e `cd` a `systeminfo`, `ping`, `tracert` e `tasklist`
- 🕹️ **Histórico de comandos** — navegação com as teclas ↑↓
- 🔤 **Autocompletar com Tab** — igual ao terminal real
- 🎨 **Comando `color`** — mudar cor do fundo e do texto (16 opções)
- 🪟 **Controles de janela** — arrastar, maximizar, minimizar, fechar
- 📦 **Zero dependências** — arquivo único, sem bibliotecas

-----

## 🚀 Início rápido

### Opção 1 — Abrir online

Acesse: **<https://prowindows4554-offical.github.io/cmd-simulator>**

### Opção 2 — Executar localmente

```bash
git clone https://github.com/prowindows4554-offical/cmd-simulator.git
cd cmd-simulator
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

-----

## 📋 Comandos suportados

<details>
<summary><b>📂 Arquivos & Diretórios</b> (clique para expandir)</summary>

|Comando           |Descrição                  |
|------------------|---------------------------|
|`dir [caminho]`   |Listar arquivos e pastas   |
|`cd [caminho]`    |Mudar diretório            |
|`mkdir [nome]`    |Criar diretório            |
|`rmdir [nome]`    |Remover diretório          |
|`del [arquivo]`   |Deletar arquivo            |
|`copy [src] [dst]`|Copiar arquivo             |
|`move [src] [dst]`|Mover arquivo              |
|`ren [src] [dst]` |Renomear arquivo           |
|`type [arquivo]`  |Mostrar conteúdo do arquivo|
|`tree [caminho]`  |Exibir árvore de diretórios|

</details>

<details>
<summary><b>🖥️ Sistema</b></summary>

|Comando         |Descrição                         |
|----------------|----------------------------------|
|`ver`           |Versão do Windows                 |
|`systeminfo`    |Informações detalhadas do sistema |
|`tasklist`      |Listar processos em execução      |
|`chkdsk`        |Verificar integridade do disco    |
|`sfc`           |Verificador de arquivos do sistema|
|`shutdown /s`   |Desligar                          |
|`whoami`        |Usuário atual                     |
|`hostname`      |Nome do computador                |
|`set [variável]`|Variáveis de ambiente             |
|`date` / `time` |Exibir data e hora                |

</details>

<details>
<summary><b>🌐 Rede</b></summary>

|Comando          |Descrição           |
|-----------------|--------------------|
|`ping [host]`    |Pingar um host      |
|`ipconfig`       |Configuração de rede|
|`netstat`        |Conexões ativas     |
|`tracert [host]` |Rastrear rota       |
|`nslookup [host]`|Consulta DNS        |
|`arp`            |Tabela ARP          |
|`net user`       |Usuários do sistema |

</details>

<details>
<summary><b>🎨 Terminal</b></summary>

|Comando         |Descrição                   |
|----------------|----------------------------|
|`cls`           |Limpar a tela               |
|`echo [texto]`  |Imprimir texto              |
|`color [código]`|Mudar cores (ex. `color 0A`)|
|`title [texto]` |Definir título da janela    |
|`prompt [texto]`|Mudar string do prompt      |
|`help`          |Listar todos os comandos    |
|`exit`          |Fechar terminal             |

</details>

-----

## 📁 Estrutura do projeto

```
cmd-simulator/
│
├── index.html       # O simulador completo — um único arquivo
├── README.md        # Documentação (English)
├── LICENSE          # Licença MIT
├── CHANGELOG.md     # Histórico de versões
├── .gitignore       # Regras Git ignore
└── docs/
    ├── README.fr.md # Documentação (Français)
    ├── README.pt.md # Documentação (Português)
    ├── README.kk.md # Documentação (Қазақша)
    └── README.ru.md # Documentação (Русский)
```

-----

## 🛠️ Stack tecnológica

Construído **sem frameworks ou dependências** — HTML, CSS e JavaScript puros:

- ⚡ Carregamento instantâneo
- 📦 Tamanho ~25 KB
- 🔒 Sem requisições externas
- 💡 Fácil de ler e modificar

-----

## 🤝 Contribuindo

Contribuições são bem-vindas! Como contribuir:

1. **Fork** o repositório
1. Crie uma branch: `git checkout -b feature/novo-comando`
1. Commit suas mudanças: `git commit -m 'Adicionar comando'`
1. Push para a branch: `git push origin feature/novo-comando`
1. Abra um **Pull Request**

-----

## 📋 Changelog

Veja [CHANGELOG](../CHANGELOG.md) para o histórico de versões.

-----

## 📄 Licença

Distribuído sob a **Licença MIT**. Veja [LICENSE](../LICENSE) para detalhes.

-----

<div align="center">

Feito com ❤️ por [ProWin Team](https://github.com/prowindows4554-offical) | Dê uma ⭐ se gostar!

</div>