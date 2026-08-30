<h1 align="center">Olá! Eu sou Matheus Silva 👋</h1>

<h3 align="center">Desenvolvedor de Software | Web, Back-end, APIs e Mobile</h3>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" />
</p>

---

## 👨‍💻 Sobre mim

Sou desenvolvedor de software com experiência prática no desenvolvimento de sistemas completos, atuando no desenvolvimento de interfaces Web, back-end, APIs REST, bancos de dados e aplicações Mobile.

Tenho experiência com **JavaScript, TypeScript, PHP, Node.js, Flutter, Dart e MySQL**, desenvolvendo soluções completas que integram diferentes camadas de uma aplicação.

Meu foco é transformar necessidades reais em sistemas funcionais, buscando criar soluções organizadas, eficientes e fáceis de utilizar.

Atualmente curso **Análise e Desenvolvimento de Sistemas (ADS)** e continuo aprimorando meus conhecimentos por meio do desenvolvimento de projetos próprios e da resolução de problemas práticos.

---

## 🛠️ Stack técnica

| Categoria          | Tecnologias                       |
| ------------------ | --------------------------------- |
| **Linguagens**     | JavaScript, TypeScript, PHP, Dart |
| **Back-end**       | Node.js, Express, PHP, APIs REST  |
| **Front-end Web**  | HTML5, CSS3, JavaScript           |
| **Mobile**         | Flutter, Dart                     |
| **Banco de dados** | MySQL                             |
| **Autenticação**   | JWT, bcrypt, Google OAuth         |
| **Ferramentas**    | Git, GitHub, VS Code              |

---

## 🚀 Projetos em destaque

### 💰 Sistema de Gestão Financeira — Unic Serviços

Sistema completo de gestão financeira desenvolvido para gerenciamento de operações financeiras, dividido em dois módulos independentes e integrado também a uma aplicação mobile em Flutter.

O projeto possui uma arquitetura composta por aplicações Web, APIs REST, bancos de dados MySQL independentes e aplicativo Mobile.

### 🏗️ Arquitetura

```text
Sistema de Gestão Financeira
│
├── 💳 Troca Contas
│   ├── Aplicação Web
│   ├── API Node.js / Express
│   └── Banco MySQL próprio
│
├── 🧾 Troca Cheque
│   ├── Aplicação Web
│   ├── API Node.js / Express
│   └── Banco MySQL próprio
│
└── 📱 Aplicativo Mobile
    └── Flutter / Dart
        ├── Troca Contas
        └── Troca Cheque
```

O aplicativo mobile funciona como uma aplicação unificada, permitindo ao usuário acessar os dois módulos através de uma única experiência.

A autenticação principal é realizada pelo backend do módulo **Troca Contas**, utilizando tokens JWT compartilhados pelo aplicativo para autenticar as requisições aos dois módulos.

### 💳 Módulo Troca Contas

Sistema para gerenciamento de operações financeiras e controle de clientes, parcelas e recebimentos.

**Principais funcionalidades:**

* Cadastro e gerenciamento de usuários
* Cadastro e gerenciamento de clientes
* Criação e gerenciamento de operações financeiras
* Operações de empréstimo e venda parcelada
* Controle de parcelas e vencimentos
* Registro de pagamentos
* Cálculo de juros
* Cálculo de multas e mora
* Dashboard com indicadores financeiros
* Agenda de vencimentos
* Relatórios
* Gerenciamento de perfil
* Sistema de planos
* Recuperação de senha
* Autenticação com email e senha
* Autenticação com Google
* API REST para comunicação entre frontend e backend

**Stack:** Node.js • Express • JavaScript • MySQL • HTML5 • CSS3 • APIs REST • JWT

### 🧾 Módulo Troca Cheque

Sistema para gerenciamento de cheques pré-datados, permitindo controlar clientes, cheques, vencimentos, valores e operações realizadas.

**Principais funcionalidades:**

* Cadastro e gerenciamento de clientes
* Cadastro de cheques
* Controle de bancos, agência e conta
* Cálculo de juros e valor líquido
* Controle de vencimentos
* Controle de status dos cheques
* Dashboard financeiro
* Alertas de vencimento
* Relatórios por cliente e banco
* Histórico de operações
* Backup e restauração de dados
* Integração com WhatsApp
* Modo discreto para ocultação de valores
* API REST
* Autenticação baseada em JWT

**Stack:** Node.js • Express • JavaScript • MySQL • HTML5 • CSS3 • APIs REST • JWT

### 📱 Aplicativo Mobile

Aplicativo desenvolvido em **Flutter e Dart**, reunindo os módulos Troca Contas e Troca Cheque em uma única aplicação.

O aplicativo consome as APIs REST dos dois módulos e possui uma arquitetura organizada por módulos, com separação entre telas, modelos, serviços e componentes compartilhados.

**Principais características:**

* Login unificado
* Cadastro de usuários
* Login com Google
* Seleção de módulo
* Troca Contas
* Troca Cheque
* Dashboard financeiro
* Gerenciamento de clientes
* Gerenciamento de operações
* Gerenciamento de parcelas
* Gerenciamento de cheques
* Relatórios
* Perfil do usuário
* Comunicação com APIs REST
* Armazenamento seguro do token de autenticação
* Notificações locais
* Interface adaptada para dispositivos móveis

**Stack:** Flutter • Dart • Dio • MySQL • Node.js • APIs REST • JWT

---

### 🏭 Sistema de Gestão de Cortes — JEE Confecções

Sistema desenvolvido para uma oficina de costura, com o objetivo de centralizar o gerenciamento de clientes, cortes e acompanhamento das etapas de produção. Possui uma aplicação Web (PHP) e um aplicativo Mobile (Flutter) que consome o mesmo backend PHP já existente, sem duplicar regras de negócio.

### 🏗️ Arquitetura

```text
Sistema de Gestão de Cortes — JEE Confecções
│
├── 🌐 Aplicação Web
│   ├── PHP (backend/API)
│   ├── MySQL
│   └── HTML5 / CSS3 / JavaScript
│
└── 📱 Aplicativo Mobile
    └── Flutter / Dart
        └── Consome o mesmo backend PHP da versão Web
```

**Principais funcionalidades:**

* Login e autenticação
* Cadastro e gerenciamento de clientes (internos e externos)
* Cadastro e gerenciamento de cortes
* Controle de quantidade de peças, referências, tecidos e grades (tamanhos adulto e infantil)
* Acompanhamento das etapas de produção (oficina, produção, lavanderia, revisão, entregue)
* Consulta e filtros de registros
* Edição e exclusão de cortes
* Dashboard com indicadores e resumo de produção
* Geração de relatórios em PDF
* Compartilhamento de relatórios via WhatsApp

**Stack Web:** PHP • MySQL • JavaScript • HTML5 • CSS3
**Stack Mobile:** Flutter • Dart • HTTP • Shared Preferences • fl_chart

---

### 🎟️ Sistema de Criação e Gestão de Rifas

Sistema desenvolvido para criação e gerenciamento de rifas, permitindo administrar usuários, rifas e participações através de uma aplicação integrada a API e banco de dados.

**Principais funcionalidades:**

* Criação e gerenciamento de rifas
* Cadastro e gerenciamento de usuários
* Participação em rifas
* Gerenciamento das informações das rifas
* Integração entre aplicação, API e banco de dados

**Stack:** Node.js • JavaScript • MySQL • APIs REST

---

## 📚 Formação

🎓 **Análise e Desenvolvimento de Sistemas (ADS)**
*Em andamento*

A formação acadêmica complementa a experiência prática adquirida através do desenvolvimento de sistemas e projetos próprios.

---

## 🎯 Objetivo profissional

Busco uma oportunidade na área de **desenvolvimento de software**, especialmente em posições **Web, Back-end ou Full Stack**, onde eu possa contribuir com minha experiência prática, trabalhar em equipe, aprender com profissionais mais experientes e continuar evoluindo tecnicamente.

Tenho interesse em atuar no desenvolvimento de aplicações completas, APIs, sistemas Web, bancos de dados e aplicações Mobile.

---

## 📫 Contato

* 💼 **LinkedIn:** adicione aqui o link do seu LinkedIn
* 📧 **E-mail:** adicione aqui seu e-mail profissional
* 🌐 **Portfólio:** adicione aqui o link do seu portfólio, quando estiver disponível

---

<p align="center">
  <i>Construindo soluções através de código, aprendizado contínuo e projetos reais.</i>
</p>
