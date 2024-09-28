# CRUD Django

Este é um projeto simples de CRUD (Create, Read, Update, Delete) desenvolvido com o framework Django. O objetivo do projeto é gerenciar uma lista de pessoas, permitindo adicionar, visualizar, editar e excluir registros.

## Tecnologias Utilizadas

- Python 3.12.1
- Django 5.1.1
- SQLite (banco de dados padrão do Django)

## Funcionalidades
- Criar: Adicionar novos registros de pessoas.
- Ler: Listar e visualizar detalhes de pessoas cadastradas.
- Atualizar: Editar informações de uma pessoa existente.
- Deletar: Excluir registros de pessoas.

## Pré-requisitos
Antes de começar, você precisará ter as seguintes ferramentas instaladas em sua máquina:

- **Python 3**
- **Pip** para gerenciar pacotes Python
- **Virtualenv** para criar um ambiente virtual isolado (opcional, mas recomendado)

## Rotas
- **/**: Página inicial, lista de pessoas cadastradas.

- **/salvar/**: Página para adicionar uma nova pessoa.

- **/editar/<int:id>/**: Página para editar os dados de uma pessoa existente.

- **/delete/<int:id>/**: Excluir uma pessoa.

## Contato

- Authors: <a href="https://github.com/LucaoCode">Lucas Lima Campos</a>
- Linkedin: <a href="https://www.linkedin.com/in/lucaslimacampos/">Linkedin</a>