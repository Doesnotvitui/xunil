# XUNIL - Sistema de Gerenciamento de Arquivos e Permissões

XUNIL é um projeto em Rust que simula um sistema básico de gerenciamento de arquivos, diretórios, usuários e grupos, com controle de permissões. O projeto foi desenvolvido como uma aplicação de linha de comando (CLI) para demonstrar conceitos de estruturas de dados, manipulação de arquivos e permissões em um sistema operacional.

## Funcionalidades

- **Gerenciamento de Arquivos**:
  - Criação de arquivos com nome, tamanho, permissões, UID e GID.
  - Listagem de arquivos com detalhes como permissões e proprietário.
  - Alteração de permissões de arquivos.

- **Gerenciamento de Diretórios**:
  - Criação de diretórios com nome, permissões e dono.
  - Adição e remoção de arquivos em diretórios.
  - Listagem do conteúdo de diretórios.

- **Gerenciamento de Usuários**:
  - Criação de usuários com nome, UID e grupo principal.
  - Adição e remoção de grupos secundários para usuários.
  - Listagem de usuários e seus grupos.

- **Gerenciamento de Grupos**:
  - Criação de grupos com nome e GID.
  - Adição e remoção de membros em grupos.
  - Listagem de grupos e seus membros.

## Estrutura do Projeto

O projeto é organizado em módulos que representam as principais entidades do sistema:

- **Arquivo**: Representa um arquivo com nome, tamanho, permissões e informações de proprietário.
- **Diretório**: Representa um diretório que contém uma lista de arquivos.
- **Usuário**: Representa um usuário do sistema, com UID, grupo principal e grupos secundários.
- **Grupo**: Representa um grupo de usuários, com GID e lista de membros.
