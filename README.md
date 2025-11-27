<div align="center">

  # 🎨 VenezArt
  
  **Sua loja virtual de materiais artísticos premium.**
  
  ![React](https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react)
  ![Flask](https://img.shields.io/badge/Backend-Flask-black?style=for-the-badge&logo=flask)
  ![SQLite](https://img.shields.io/badge/Database-SQLite-blue?style=for-the-badge&logo=sqlite)
  ![Python](https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge&logo=python)

  [Sobre](#-sobre) • [Funcionalidades](#-funcionalidades) • [Tecnologias](#-tecnologias) • [Instalação](#-instalação) • [Equipe](#-autores)

</div>

---

## 🖼 Visão Geral

O **VenezArt** é uma plataforma de e-commerce focada em produtos para pintura em tela, desenvolvida para proporcionar uma experiência de compra fluida e uma gestão administrativa eficiente.

Este projeto foi concebido como parte do **Projeto Semestral do curso de Análise e Desenvolvimento de Sistemas – IFSP**, demonstrando a integração de uma arquitetura moderna (SPA) com uma API RESTful robusta.

---

## 📸 Screenshots

> *Dica: Insira aqui gifs ou imagens do seu sistema funcionando.*

| Home Page | Carrinho de Compras |
|:---:|:---:|
| ![Home](https://via.placeholder.com/400x200?text=Home+Page+VenezArt) | ![Carrinho](https://via.placeholder.com/400x200?text=Carrinho+de+Compras) |

---

## 🚀 Funcionalidades

### 👤 Área do Cliente
- [x] **Catálogo Interativo:** Navegação fluida por produtos de arte.
- [x] **Carrinho Inteligente:** Adição, remoção e cálculo em tempo real.
- [x] **Checkout Seguro:** Fluxo de finalização de pedidos.
- [x] **Comprovantes:** Geração automática de PDF detalhado da compra.
- [x] **Histórico:** Acompanhamento de pedidos anteriores.

### 🛡️ Painel Administrativo
- [x] **Gestão de Produtos:** CRUD completo (Criar, Ler, Atualizar, Deletar).
- [x] **Controle de Pedidos:** Visualização de status e detalhes de vendas.
- [x] **Relatórios:** Exportação de dados estratégicos em **Excel** e **PDF**.
- [x] **Segurança:** Autenticação via JWT para proteção de rotas.

---

## 🛠 Tecnologias Utilizadas

### **Frontend** (Interface)
- **Framework:** React + Vite
- **Estilização:** CSS3 Moderno / Styled Components (se houver)
- **Linguagem:** JavaScript (ES2024)

### **Backend** (API & Regras de Negócio)
- **Framework:** Flask (Python)
- **Segurança:** Flask-JWT-Extended & Werkzeug Security
- **ORM:** SQLAlchemy
- **Utilitários:** ReportLab (PDFs), Pandas/Openpyxl (Excel)

### **Infraestrutura & Dados**
- **Banco de Dados:** SQLite (Leve e eficiente para a proposta)
- **Gerenciador de Pacotes:** PIP & NPM

---

## 📂 Estrutura do Projeto

```bash
VenezArt/
├── backend/
│   ├── app.py             # Ponto de entrada da API
│   ├── models/            # Modelos do Banco de Dados
│   ├── routes/            # Rotas da API
│   └── services/          # Lógica de geração de arquivos
├── frontend/
│   ├── src/
│   │   ├── components/    # Componentes Reutilizáveis
│   │   ├── pages/         # Páginas da Aplicação
│   │   └── services/      # Integração com API (Axios/Fetch)
└── README.md
Aqui está uma versão revitalizada do seu README.

O que mudou para torná-lo mais profissional:

Cabeçalho Centralizado: Cria uma identidade visual forte logo de cara.

Badges Organizados: Categorização visual das tecnologias.

Seção de Screenshots: Essencial para projetos frontend (deixei espaços reservados para você colocar as imagens).

Tabela de Desenvolvedores: Usa as fotos de perfil do GitHub automaticamente, o que dá um toque muito mais humano e profissional.

Instalação Clara: Blocos de código separados para facilitar o "copiar e colar".

Estrutura de Diretórios: Mostra organização técnica.

📋 Copie o código abaixo:
Markdown

<div align="center">

  # 🎨 VenezArt
  
  **Sua loja virtual de materiais artísticos premium.**
  
  ![React](https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react)
  ![Flask](https://img.shields.io/badge/Backend-Flask-black?style=for-the-badge&logo=flask)
  ![SQLite](https://img.shields.io/badge/Database-SQLite-blue?style=for-the-badge&logo=sqlite)
  ![Python](https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge&logo=python)

  [Sobre](#-sobre) • [Funcionalidades](#-funcionalidades) • [Tecnologias](#-tecnologias) • [Instalação](#-instalação) • [Equipe](#-autores)

</div>

---

## 🖼 Visão Geral

O **VenezArt** é uma plataforma de e-commerce focada em produtos para pintura em tela, desenvolvida para proporcionar uma experiência de compra fluida e uma gestão administrativa eficiente.

Este projeto foi concebido como parte do **Projeto Semestral do curso de Análise e Desenvolvimento de Sistemas – IFSP**, demonstrando a integração de uma arquitetura moderna (SPA) com uma API RESTful robusta.

---

## 📸 Screenshots

> *Dica: Insira aqui gifs ou imagens do seu sistema funcionando.*

| Home Page | Carrinho de Compras |
|:---:|:---:|
| ![Home](https://via.placeholder.com/400x200?text=Home+Page+VenezArt) | ![Carrinho](https://via.placeholder.com/400x200?text=Carrinho+de+Compras) |

---

## 🚀 Funcionalidades

### 👤 Área do Cliente
- [x] **Catálogo Interativo:** Navegação fluida por produtos de arte.
- [x] **Carrinho Inteligente:** Adição, remoção e cálculo em tempo real.
- [x] **Checkout Seguro:** Fluxo de finalização de pedidos.
- [x] **Comprovantes:** Geração automática de PDF detalhado da compra.
- [x] **Histórico:** Acompanhamento de pedidos anteriores.

### 🛡️ Painel Administrativo
- [x] **Gestão de Produtos:** CRUD completo (Criar, Ler, Atualizar, Deletar).
- [x] **Controle de Pedidos:** Visualização de status e detalhes de vendas.
- [x] **Relatórios:** Exportação de dados estratégicos em **Excel** e **PDF**.
- [x] **Segurança:** Autenticação via JWT para proteção de rotas.

---

## 🛠 Tecnologias Utilizadas

### **Frontend** (Interface)
- **Framework:** React + Vite
- **Estilização:** CSS3 Moderno / Styled Components (se houver)
- **Linguagem:** JavaScript (ES2024)

### **Backend** (API & Regras de Negócio)
- **Framework:** Flask (Python)
- **Segurança:** Flask-JWT-Extended & Werkzeug Security
- **ORM:** SQLAlchemy
- **Utilitários:** ReportLab (PDFs), Pandas/Openpyxl (Excel)

### **Infraestrutura & Dados**
- **Banco de Dados:** SQLite (Leve e eficiente para a proposta)
- **Gerenciador de Pacotes:** PIP & NPM

---

## 📂 Estrutura do Projeto

```bash
VenezArt/
├── backend/
│   ├── app.py             # Ponto de entrada da API
│   ├── models/            # Modelos do Banco de Dados
│   ├── routes/            # Rotas da API
│   └── services/          # Lógica de geração de arquivos
├── frontend/
│   ├── src/
│   │   ├── components/    # Componentes Reutilizáveis
│   │   ├── pages/         # Páginas da Aplicação
│   │   └── services/      # Integração com API (Axios/Fetch)
└── README.md

🔧 Instalação e Execução
Pré-requisitos: Node.js e Python instalados.

1️⃣ Configurando o Backend (Servidor)
# Entre na pasta do backend
cd backend

# Crie o ambiente virtual
python -m venv venv

# Ative o ambiente virtual
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Execute a aplicação
python app.py
O servidor iniciará em http://localhost:5000

2️⃣ Configurando o Frontend (Cliente)

# Em um novo terminal, entre na pasta do frontend
cd frontend

# Instale as dependências do Node
npm install

# Inicie o projeto
npm run dev
A aplicação estará disponível em http://localhost:5173



Aqui está uma versão revitalizada do seu README.O que mudou para torná-lo mais profissional:Cabeçalho Centralizado: Cria uma identidade visual forte logo de cara.Badges Organizados: Categorização visual das tecnologias.Seção de Screenshots: Essencial para projetos frontend (deixei espaços reservados para você colocar as imagens).Tabela de Desenvolvedores: Usa as fotos de perfil do GitHub automaticamente, o que dá um toque muito mais humano e profissional.Instalação Clara: Blocos de código separados para facilitar o "copiar e colar".Estrutura de Diretórios: Mostra organização técnica.📋 Copie o código abaixo:Markdown<div align="center">

  # 🎨 VenezArt
  
  **Sua loja virtual de materiais artísticos premium.**
  
  ![React](https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react)
  ![Flask](https://img.shields.io/badge/Backend-Flask-black?style=for-the-badge&logo=flask)
  ![SQLite](https://img.shields.io/badge/Database-SQLite-blue?style=for-the-badge&logo=sqlite)
  ![Python](https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge&logo=python)

  [Sobre](#-sobre) • [Funcionalidades](#-funcionalidades) • [Tecnologias](#-tecnologias) • [Instalação](#-instalação) • [Equipe](#-autores)

</div>

---

## 🖼 Visão Geral

O **VenezArt** é uma plataforma de e-commerce focada em produtos para pintura em tela, desenvolvida para proporcionar uma experiência de compra fluida e uma gestão administrativa eficiente.

Este projeto foi concebido como parte do **Projeto Semestral do curso de Análise e Desenvolvimento de Sistemas – IFSP**, demonstrando a integração de uma arquitetura moderna (SPA) com uma API RESTful robusta.

---

## 📸 Screenshots

> *Dica: Insira aqui gifs ou imagens do seu sistema funcionando.*

| Home Page | Carrinho de Compras |
|:---:|:---:|
| ![Home](https://via.placeholder.com/400x200?text=Home+Page+VenezArt) | ![Carrinho](https://via.placeholder.com/400x200?text=Carrinho+de+Compras) |

---

## 🚀 Funcionalidades

### 👤 Área do Cliente
- [x] **Catálogo Interativo:** Navegação fluida por produtos de arte.
- [x] **Carrinho Inteligente:** Adição, remoção e cálculo em tempo real.
- [x] **Checkout Seguro:** Fluxo de finalização de pedidos.
- [x] **Comprovantes:** Geração automática de PDF detalhado da compra.
- [x] **Histórico:** Acompanhamento de pedidos anteriores.

### 🛡️ Painel Administrativo
- [x] **Gestão de Produtos:** CRUD completo (Criar, Ler, Atualizar, Deletar).
- [x] **Controle de Pedidos:** Visualização de status e detalhes de vendas.
- [x] **Relatórios:** Exportação de dados estratégicos em **Excel** e **PDF**.
- [x] **Segurança:** Autenticação via JWT para proteção de rotas.

---

## 🛠 Tecnologias Utilizadas

### **Frontend** (Interface)
- **Framework:** React + Vite
- **Estilização:** CSS3 Moderno / Styled Components (se houver)
- **Linguagem:** JavaScript (ES2024)

### **Backend** (API & Regras de Negócio)
- **Framework:** Flask (Python)
- **Segurança:** Flask-JWT-Extended & Werkzeug Security
- **ORM:** SQLAlchemy
- **Utilitários:** ReportLab (PDFs), Pandas/Openpyxl (Excel)

### **Infraestrutura & Dados**
- **Banco de Dados:** SQLite (Leve e eficiente para a proposta)
- **Gerenciador de Pacotes:** PIP & NPM

---

## 📂 Estrutura do Projeto

```bash
VenezArt/
├── backend/
│   ├── app.py             # Ponto de entrada da API
│   ├── models/            # Modelos do Banco de Dados
│   ├── routes/            # Rotas da API
│   └── services/          # Lógica de geração de arquivos
├── frontend/
│   ├── src/
│   │   ├── components/    # Componentes Reutilizáveis
│   │   ├── pages/         # Páginas da Aplicação
│   │   └── services/      # Integração com API (Axios/Fetch)
└── README.md
🔧 Instalação e ExecuçãoPré-requisitos: Node.js e Python instalados.1️⃣ Configurando o Backend (Servidor)Bash# Entre na pasta do backend
cd backend

# Crie o ambiente virtual
python -m venv venv

# Ative o ambiente virtual
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Execute a aplicação
python app.py
O servidor iniciará em http://localhost:50002️⃣ Configurando o Frontend (Cliente)Bash# Em um novo terminal, entre na pasta do frontend
cd frontend

# Instale as dependências do Node
npm install
 AutoresProjeto desenvolvido por estudantes do IFSP.<img src="https://github.com/GeisieleOliveira.png" width="100px;"/><br /><sub><b>Geisiele Oliveira</b></sub><img src="https://github.com/Thiagolvc.png" width="100px;"/><br /><sub><b>Thiago Oliveira</b></sub><img src="https://github.com/Viniciusmagal.png" width="100px;"/><br /><sub><b>Vinícius Magalhães</b></sub>
