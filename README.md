Python foi utilizado amplamente neste repositório, principalmente para criar um pequeno sistema web que serve de exemplo para uso do CodeQL. Utilizei o Python nas seguintes etapas:

Estrutura do Projeto

A pasta server/ contém vários arquivos Python:
server/__main__.py: Script principal que inicializa o banco de dados, insere livros e executa a aplicação Flask.
server/webapp.py: Define a aplicação Flask, conecta ao banco SQLite e configura caminhos de templates.
server/routes.py: Define rotas da aplicação web usando Flask, manipulando requisições e exibindo livros.
server/models/books.py: Define a classe Book usando dataclasses do Python.
server/models/__init__.py: Importa modelos Python.
Uso de Frameworks Python

É utilizado o framework Flask para criar a aplicação web.
O banco de dados é manipulado com o módulo sqlite3 do Python.
Função no repositório:

Esse código Python serve como alvo para as análises do CodeQL durante as etapas, permitindo encontrar e corrigir vulnerabilidades (como SQL Injection).
