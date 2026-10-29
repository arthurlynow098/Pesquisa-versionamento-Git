<p align="center">
  <img src="assets/banner.png" alt="Git Versionamento" width="100%">
</p>

<p align="center">
  Guia técnico e ambiente prático sobre controle de versão distribuído com Git, fluxo local de commits, branches e linha de comando.
</p>

<p align="center">
  <img alt="Git" src="https://img.shields.io/badge/Git-Version_Control-C52E36?style=for-the-badge&logo=git&logoColor=white">
  <img alt="CLI" src="https://img.shields.io/badge/Terminal-Git_CLI-11120F?style=for-the-badge&logo=gnubash&logoColor=C52E36">
  <img alt="PDF + Web" src="https://img.shields.io/badge/Material-PDF_%2B_Web_Lab-18181B?style=for-the-badge">
</p>

## Sobre o projeto

Dominar o **Git** pelo terminal é uma habilidade indispensável para qualquer equipe de engenharia de software. Este repositório reúne uma pesquisa técnica completa em PDF (Pesquisa-Git-Fluxo-Local.pdf) e um laboratório prático (projeto-web/) criado especificamente para demonstrar na prática o funcionamento da *Working Tree*, *Staging Area (Index)*, histórico de commits e arquivo .gitignore.

O diretório projeto-web/ simula a estrutura real de uma aplicação front-end — incluindo código-fonte (index.html, style.css, pp.js), arquivos de log (logs/app.log), dependências simuladas (
ode_modules/) e uma folha de referência rápida de comandos (comandos.txt).

## Principais recursos

| Recurso | Como funciona |
|---|---|
| Documento Técnico em PDF | Pesquisa-Git-Fluxo-Local.pdf detalha os estados dos arquivos (untracked, modified, staged, committed) e a anatomia do fluxo local. |
| Laboratório Prático (projeto-web) | Projeto web funcional projetado para testar git status, git add, git diff, git commit e git log. |
| Cenário de .gitignore | Inclui diretórios logs/ e 
ode_modules/ para demonstrar como ignorar artefatos temporários e pacotes de terceiros. |
| Guia de Comandos (comandos.txt) | Roteiro passo a passo de comandos de terminal usados durante a apresentação prática. |

## Tecnologias

<p>
  <img alt="Git" src="https://img.shields.io/badge/Git-C52E36?style=flat-square&logo=git&logoColor=white">
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-11120F?style=flat-square&logo=github&logoColor=C52E36">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-C52E36?style=flat-square&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-11120F?style=flat-square&logo=css3&logoColor=C52E36">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-C52E36?style=flat-square&logo=javascript&logoColor=white">
</p>

## Arquitetura do fluxo Git estudado

`mermaid
flowchart LR
    A[Working Directory · projeto-web] -->|git add| B[Staging Area · Index]
    B -->|git commit -m| C[Repositório Local · .git]
    C -->|git push| D[Repositório Remoto · GitHub]
    E[logs/ & node_modules/] -.->| Filtrados por .gitignore | A
`

## Estrutura do repositório

`	ext
Pesquisa-versionamento-Git/
├── assets/
│   ├── banner.png                      Banner principal do repositório
│   └── project-animal.png              Símbolo do pica-pau
├── projeto-web/
│   ├── assets/                         style.css e app.js da aplicação demonstrativa
│   ├── logs/app.log                    Exemplo de arquivo de log para teste de .gitignore
│   ├── node_modules/                   Exemplo de diretório de dependências
│   ├── comandos.txt                    Referência rápida de comandos Git no terminal
│   ├── index.html                      Página principal do projeto demonstrativo
│   └── README.md                       Instruções específicas do laboratório
├── Pesquisa-Git-Fluxo-Local.pdf        Artigo e apresentação sobre fluxo local no Git
└── README.md
`

## Como explorar

1. Clone o repositório:
   `ash
   git clone https://github.com/arthurlynow098/Pesquisa-versionamento-Git.git
   `
2. Abra o documento [Pesquisa-Git-Fluxo-Local.pdf](Pesquisa-Git-Fluxo-Local.pdf) para acompanhar a fundamentação teórica.
3. Acesse a pasta projeto-web/, consulte comandos.txt e abra projeto-web/index.html no navegador.

---

<p align="center"><sub>Estudo · construção · evolução</sub><br><a href="https://github.com/arthurlynow098">Perfil</a> · <a href="https://arthurentsev.vercel.app/">Portfólio</a> · <a href="https://www.linkedin.com/in/entsevarthur/">LinkedIn</a></p>
