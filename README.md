<div align="center">

# 🎨 VenezArt

**Sua loja virtual de materiais artísticos premium.**

![React](https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react)
![Flask](https://img.shields.io/badge/Backend-Flask-black?style=for-the-badge&logo=flask)
![SQLite](https://img.shields.io/badge/Database-SQLite-blue?style=for-the-badge&logo=sqlite)
![Python](https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge&logo=python)

[Sobre](#-sobre) • [Funcionalidades](#-funcionalidades) • [Tecnologias](#-tecnologias) • [Instalação](#-instalação) • [Autores](#-autores)

</div>

---

## 🖼 Sobre

O **VenezArt** é uma plataforma de e-commerce focada na venda de materiais para pintura em tela.

O projeto foi desenvolvido como parte do **Projeto Semestral do curso de Análise e Desenvolvimento de Sistemas – IFSP**, utilizando uma arquitetura moderna com frontend separado do backend via API REST.

---


## 🚀 Funcionalidades

### 👤 Cliente
- Catálogo de produtos
- Carrinho de compras dinâmico
- Finalização de pedidos
- Geração de comprovante em PDF
- Histórico de pedidos

### 🔐 Administrativo
- CRUD de produtos
- Gestão de pedidos
- Exportação em PDF e Excel
- Autenticação com JWT

---

## 🛠 Tecnologias

### Frontend
- React + Vite
- JavaScript (ES2024)
- CSS3

### Backend
- Flask (Python)
- Flask-JWT-Extended
- SQLAlchemy
- ReportLab (PDF)
- Pandas / OpenPyXL (Excel)

### Banco de Dados
- SQLite

---

## 📂 Estrutura do Projeto

```bash
VenezArt/
├── backend/
│   ├── app.py
│   ├── models/
│   ├── routes/
│   └── services/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── services/
└── README.md
```

---
##🔧 Instalação e Execução
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

# Autores 👨‍💻 
Projeto desenvolvido com 💜 por estudantes do IFSP.
<table align="center">
  <tr>
    <td align="center" style="padding: 15px;">
      <img src="https://avatars.githubusercontent.com/Viniciusmagal" width="80" style="border-radius: 50%;"/><br>
      <b>Vinícius Magalhães</b><br>
      <a href="https://github.com/Viniciusmagal" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-Viniciusmagal-black?style=for-the-badge&logo=github"/>
      </a>
    </td>

    <td align="center" style="padding: 15px;">
      <img src="https://avatars.githubusercontent.com/GeisieleOliveira" width="80" style="border-radius: 50%;"/><br>
      <b>Geisiele Oliveira</b><br>
      <a href="https://github.com/GeisieleOliveira" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-GeisieleOliveira-black?style=for-the-badge&logo=github"/>
      </a>
    </td>
  </tr>

  <tr>
    <td align="center" style="padding: 15px;">
      <img src="https://avatars.githubusercontent.com/Thiagolvc" width="80" style="border-radius: 50%;"/><br>
      <b>Thiago</b><br>
      <a href="https://github.com/Thiagolvc" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-Thiagolvc-black?style=for-the-badge&logo=github"/>
      </a>
    </td>

    <td align="center" style="padding: 15px;">
      <img src="https://avatars.githubusercontent.com/vinolass" width="80" style="border-radius: 50%;"/><br>
      <b>Vinolass</b><br>
      <a href="https://github.com/vinolass" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-vinolass-black?style=for-the-badge&logo=github"/>
      </a>
    </td>
  </tr>
</table>
