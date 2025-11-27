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

## 🛠 Tecnologias Utilizadas no Projeto

---

| Tecnologia | Descrição |
|-----------|-----------|
| ![React](https://img.shields.io/badge/REACT-20232A?style=for-the-badge&logo=react) | **Frontend — React + Vite**<br><br>O frontend da aplicação foi construído utilizando React aliado ao Vite, que oferece um ambiente de desenvolvimento moderno, rápido e eficiente.<br><br>**Por que React?**<br>• Permite criar interfaces dinâmicas e componentes reutilizáveis.<br>• Facilita a organização do código com componentes separados.<br>• Sincroniza facilmente com a API Flask através de requisições HTTP.<br><br>**Por que Vite?**<br>• Tem um servidor de desenvolvimento extremamente rápido.<br>• Build mais leve e otimizado.<br>• Melhor experiência com Hot Module Replacement (atualização automática sem recarregar a página).<br><br>**Funcionalidades no Frontend:**<br>• Páginas e componentes do usuário e administrador<br>• Listagem de produtos<br>• Carrinho de compras<br>• Sistema de login e cadastro<br>• Área administrativa com gerenciamento de pedidos<br>• Consumo da API Flask utilizando fetch ou axios<br>• Interface responsiva e atualizações em tempo real através do estado do React |
| ![Python](https://img.shields.io/badge/PYTHON-306998?style=for-the-badge&logo=python&logoColor=white) | **Linguagem Python + Flask (Backend)**<br><br>O backend da aplicação foi desenvolvido em Python, escolhida por ser uma linguagem simples, poderosa e com um ecossistema robusto. O framework principal utilizado foi o Flask, que permitiu criar a API de forma leve, organizada e eficiente.<br><br>**Recursos do Flask utilizados:**<br>• Roteamento da API — responsável por gerenciar todas as rotas da aplicação: login, produtos, pedidos, carrinho, favoritos etc.<br>• request — usado para capturar dados enviados do frontend.<br>• jsonify — converte as respostas da API em JSON.<br>• session — guarda informações temporárias do usuário quando necessário.<br>• send_file — envia arquivos gerados dinamicamente (PDF e Excel).<br><br>**Autenticação (Flask-JWT-Extended):**<br>• create_access_token — gera tokens JWT.<br>• jwt_required — protege rotas.<br>• get_jwt_identity — identifica o usuário logado.<br><br>**Segurança de senhas (Werkzeug):**<br>• generate_password_hash — cria hash seguro para senha.<br>• check_password_hash — valida a senha no login. |
| ![Flask](https://img.shields.io/badge/FLASK-000000?style=for-the-badge&logo=flask) | **Geração de Arquivos (PDF e Excel)**<br><br>• ReportLab — responsável pela criação de PDFs (tabelas, estilização e layout).<br>• openpyxl + pandas — usados para gerar planilhas Excel, especialmente para o administrador.<br>• BytesIO — permite gerar os arquivos em memória, sem salvar no disco.<br><br>**Outras bibliotecas úteis:**<br>• datetime — manipulação de datas (ex.: data do pedido).<br>• re — validações com expressões regulares.<br>• os e requests — manipulação de arquivos e comunicação externa.<br>• pytz — gerenciamento de fuso horário. |
| ![SQLite](https://img.shields.io/badge/SQLITE-003B57?style=for-the-badge&logo=sqlite&logoColor=white) | **Banco de Dados — SQLite**<br><br>Para armazenar dados, foi utilizado o SQLite, um banco de dados leve e simples que não exige servidor externo, ideal para aplicações pequenas e médias.<br><br>**Por que SQLite?**<br>• Não precisa de instalação de servidor.<br>• Perfeito para desenvolvimento local e projetos simples.<br>• Integrado facilmente ao SQLAlchemy.<br><br>**Modelos do Banco (ORM):**<br>• User — usuários da aplicação<br>• Product — produtos cadastrados<br>• CartItem — itens no carrinho<br>• Pedido — pedidos realizados<br>• PedidoItem — itens dentro de cada pedido<br>• Favorite — produtos favoritados |

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
## 🔧 Instalação e Execução
Pré-requisitos: Node.js e Python instalados.

1️⃣ Configurando o Backend (Servidor)
Entre na pasta do backend
cd backend

Crie o ambiente virtual
python -m venv venv

Ative o ambiente virtual
Windows:
venv\Scripts\activate
Linux/Mac:
source venv/bin/activate

Instale as dependências
pip install -r requirements.txt

Execute a aplicação
python app.py
O servidor iniciará em http://localhost:5000

2️⃣ Configurando o Frontend (Cliente)
Em um novo terminal, entre na pasta do frontend
cd frontend

Instale as dependências do Node
npm install

Inicie o projeto
npm run dev
A aplicação estará disponível em http://localhost:5173

---

## 👨‍💻 Autores

Projeto desenvolvido com 💜 por estudantes do IFSP.

<table align="center">
  <tr>
<td align="center" width="200px">
      <img src="https://avatars.githubusercontent.com/u/155771396?v=4" width="100" height="100" style="border-radius:50%; object-fit:cover;"/><br>
      <b>Geisiele Oliveira</b><br>
      <a href="https://github.com/GeisieleOliveira" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-GeisieleOliveira-black?style=for-the-badge&logo=github"/>
      </a>
    </td>
     <td align="center" width="200px">
      <img src="https://avatars.githubusercontent.com/Thiagolvc" width="100" height="100" style="border-radius:50%; object-fit:cover;"/><br>
      <b>Thiago Camargo</b><br>
      <a href="https://github.com/Thiagolvc" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-Thiagolvc-black?style=for-the-badge&logo=github"/>
      </a>
    </td>
    <td align="center" width="200px">
      <img src="https://avatars.githubusercontent.com/vinolass" width="100" height="100" style="border-radius:50%; object-fit:cover;"/><br>
      <b>Vinicius Arantes</b><br>
      <a href="https://github.com/vinolass" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-vinolass-black?style=for-the-badge&logo=github"/>
      </a>
    </td>
   <td align="center" width="200px">
      <img src="https://avatars.githubusercontent.com/Viniciusmagal" width="100" height="100" style="border-radius:50%; object-fit:cover;"/><br>
      <b>Vinicius Magalhães</b><br>
      <a href="https://github.com/Viniciusmagal" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-Viniciusmagal-black?style=for-the-badge&logo=github"/>
      </a>
    </td>
  </tr>
</table>
