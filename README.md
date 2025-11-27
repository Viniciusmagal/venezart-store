🛠 Tecnologias Utilizadas no Projeto

Este projeto foi desenvolvido integrando três pilares principais: Frontend com React + Vite, Backend com Python e Flask, e Banco de Dados SQLite.
A seguir, apresentamos um resumo organizado das ferramentas utilizadas e seus papéis dentro da aplicação.

🎨 Frontend — React + Vite

O frontend da aplicação foi construído utilizando React aliado ao Vite, que oferece um ambiente de desenvolvimento moderno, rápido e eficiente.

💡 Por que React?

Permite criar interfaces dinâmicas e componentes reutilizáveis.

Facilita a organização do código com componentes separados.

Sincroniza facilmente com a API Flask através de requisições HTTP.

⚡ Por que Vite?

Tem um servidor de desenvolvimento extremamente rápido.

Build mais leve e otimizado.

Melhor experiência com Hot Module Replacement (atualização automática sem recarregar a página).

🔧 Funcionalidades implementadas no frontend

Páginas e componentes do usuário e administrador

Listagem de produtos

Carrinho de compras

Sistema de login e cadastro

Área administrativa com gerenciamento de pedidos

Consumo da API Flask utilizando fetch ou axios (dependendo do seu projeto)

Interface responsiva e atualizações em tempo real através do estado do React

🐍 Linguagem Python + Flask (Backend)

O backend da aplicação foi desenvolvido em Python, escolhida por ser uma linguagem simples, poderosa e com um ecossistema robusto.
O framework principal utilizado foi o Flask, que permitiu criar a API de forma leve, organizada e eficiente.

🔧 Recursos do Flask utilizados

Roteamento da API
Responsável por gerenciar todas as rotas da aplicação: login, produtos, pedidos, carrinho, favoritos etc.

request
Usado para capturar dados enviados do frontend.

jsonify
Converte as respostas da API em JSON.

session
Guarda informações temporárias do usuário quando necessário.

send_file
Envia arquivos gerados dinamicamente (PDF e Excel).

🔐 Autenticação

Utilizando Flask-JWT-Extended:

create_access_token – Gera tokens JWT.

jwt_required – Protege rotas.

get_jwt_identity – Identifica o usuário logado.

🔑 Segurança de senhas

Usando Werkzeug Security:

generate_password_hash – Cria hash seguro para senha.

check_password_hash – Valida a senha no login.

📄 Geração de arquivos (PDF e Excel)

ReportLab — responsável pela criação de PDFs (tabelas, estilização, layout).

openpyxl + pandas — usados para gerar planilhas Excel, especialmente para o administrador.

BytesIO — permite gerar os arquivos em memória, sem salvar no disco.

📘 Outras bibliotecas úteis

datetime — manipulação de datas (ex.: data do pedido).

re — validações com expressões regulares.

os e requests — manipulação de arquivos e comunicação externa.

pytz — gerenciamento de fuso horário.

🗄 Banco de Dados — SQLite

Para armazenar dados, foi utilizado o SQLite, um banco de dados leve e simples que não exige servidor externo, ideal para aplicações pequenas e médias.

✔ Por que SQLite?

Não precisa de instalação de servidor.

Perfeito para desenvolvimento local e projetos simples.

Integrado facilmente ao SQLAlchemy.

🧱 Modelos do Banco (ORM)

Utilizando SQLAlchemy, os principais modelos criados foram:

User — usuários da aplicação

Product — produtos cadastrados

CartItem — itens no carrinho

Pedido — pedidos realizados

PedidoItem — itens dentro de cada pedido

Favorite — produtos favoritados

Esses modelos representam as tabelas do banco e permitem executar operações de forma prática e segura.
