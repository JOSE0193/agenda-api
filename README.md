# 📅 Agenda API

## Descrição
O **Agenda API** é uma projeto backend desenvolvido em Spring. Essa API oferece funcionalidades como criar, listar, editar e remover clientes e seus respectivos agendamentos persistindo tais integrações em um banco de dados relacional OracleDB.

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Oracle DB](https://img.shields.io/badge/Oracle%20DB-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

## Funcionalidades
- 🔐 – **Sistema de Autenticação**: Sistema de autenticação utilizando spring security.
- 🧑‍💻 **Gerenciamento de agendamentos**: CRUD de para cadastro de clientes e agendamentos dos atendimentos.
- 🔗 **Integração com WEB **: Integração plataforma front-end web desenvolvida com Angular e bootstrap.

## Tecnologias Utilizadas
- **Java e Maven**: Ambiente de execução para construir a API.
- **Spring-Framework**: Framework flexível para a construção de APIs.
- **Oracle**: Banco de dados SQL para armazenar as informações de clientes e agendamentos.
- **Hibernate**: Biblioteca para integração com o banco de dados.

## Como rodar o projeto
### Pré-requisitos
- **Java** instalado (17)
- **IDE com suporte a Maven** Recomendado intellij community
- **Oracle** rodando localmente
- **Git** para clonar o repositório

### Passo a passo

1. **Clone o repositório**:
    ```bash
    git clone https://github.com/JOSE0193/agenda-api.git
    cd agenda-api
    ```

2. **Instale as dependências**:
    ```bash
    Abra a aplicação na ide de sua preferência
    ```

3. **Inicie o servidor**:
    ```bash
    Inicie a aplicação na IDE.

## Rotas para usuários não autenticados

- **POST** `/api/users`: Rota para criar novo usuário.
- **POST** `/api/session`: Rota para login.

## Rotas para usuários autenticados
### Cliente
- **POST** `/api/clientes`: Cria uma novo cliente.
- **GET** `/api/clientes`: Lista todos os clientes.
- **GET** `/api/clientes/id`: Lista um cliente específico.
- **PUT** `/api/clientes/id`: Atualiza um cliente específico.
- **DELETE** `/api/clientes/id`: Remove um cliente específico.

### Agendamentos

- **POST** `/api/agendamentos`: Cria uma novo agendamento.
- **GET** `/api/agendamentos`: Lista todos os agendamentos.
- **GET** `/api/agendamentos/id`: Lista um agendamento específico.
- **PUT** `/api/agendamentos/id`: Atualiza um agendamento específico.
- **DELETE** `/api/agendamentos/id`: Remove um agendamento específico.

### Tratamentos

- **POST** `/api/servicos`: Cria uma novo serviços.
- **GET** `/api/serviços`: Lista todos os serviços.
- **GET** `/api/serviços/id`: Lista um agendamento específico.
- **PUT** `/api/serviços/id`: Atualiza um serviço específico.
- **DELETE** `/api/serviços/id`: Remove um serviço específico.



