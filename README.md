# 📆 Agenda de Contatos

Este é um sistema web de **agenda de contatos** desenvolvido com o framework **Django**. A aplicação permite que usuários realizem operações completas de cadastro, edição, visualização e exclusão de contatos.

O projeto foi criado com foco em praticar e aplicar os conceitos fundamentais de um CRUD (Create, Read, Update, Delete) utilizando a estrutura robusta do Django, além de organizar os dados em um banco relacional com SQLite.

O sistema está finalizado e pronto para uso local, sendo uma base sólida para projetos futuros ou como referência para quem deseja entender como estruturar uma aplicação web com Django.
---

## 🚀 Funcionalidades

- ✅ Listagem de contatos
- ➕ Adição de novos contatos
- ✏️ Edição de contatos existentes
- ❌ Exclusão de contatos
- 🔍 Filtro de busca por nome
- 💾 Armazenamento com SQLite

---

## 🛠️ Tecnologias Utilizadas

- [Python 3.x](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- HTML5, CSS3 (com Bootstrap)
- SQLite (banco de dados)

---

## 📁 Estrutura do Projeto
Agenda/ ├── agenda/ # Configuração principal do projeto Django (settings, urls, wsgi) 
├── base_static/ # Arquivos estáticos (CSS, JS, imagens) 
├── base_templates/ # Templates base HTML (layout base, herança de templates) 
├── contact/ # Aplicação de contatos (models, views, urls, forms) │ 
├── migrations/ # Migrações do banco de dados para a app contact │ 
└── ... ├── db.sqlite3 # Banco de dados SQLite ├── manage.py # Script de gerenciamento do Django 
└── requirements.txt # Lista de dependências do projeto
Copiar
Editar

---


