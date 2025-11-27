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

⚙️ Instalação
✅ Pré-requisitos
Node.js instalado
Python 3.10+ instalado

🖥 Backend (Flask)
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate

pip install -r requirements.txt

python app.py
A API vai rodar em:
👉 http://localhost:5000

💻 Frontend (React)
cd frontend

npm install

npm run dev
O site vai abrir em:
👉 http://localhost:5173

## 👥 Autores

<table>
  <tr>
    <td align="center">
      <b>Vinícius Magalhães</b><br>
      <a href="https://github.com/Viniciusmagal" target="_blank">
        <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png"/>
      </a>
    </td>
    <td align="center">
      <b>Geisiele Oliveira</b><br>
      <a href="https://github.com/GeisieleOliveira" target="_blank">
        <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png"/>
      </a>
    </td>
  </tr>
</table>
