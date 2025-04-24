# 🗂️ Gerenciador de Tarefas - MVC com Spring Boot

Projeto de uma aplicação web para gerenciamento de tarefas, seguindo a arquitetura MVC (Model-View-Controller), com persistência de dados em MariaDB, MongoDB e H2 para testes locais.

---

## 🚀 Tecnologias Utilizadas

- **Java 21**
- **Spring Boot**
  - Spring Web
  - Spring Data JPA
  - Spring Data MongoDB
  - Spring Boot DevTools
  - Validation
- **Lombok**
- **Maven**
- **H2 Database** (ambiente de testes)
- **MariaDB** (persistência relacional)
- **Postman** (para testes de API)

---

## 🧠 Arquitetura MVC

A aplicação está dividida em camadas conforme o padrão MVC:

- **Model**: Representa a entidade `Tarefa`.
- **Repository**: Comunicação com os bancos de dados.
- **Service**: Lógica de negócios da aplicação.
- **Controller**: Interface RESTful para o frontend ou outras aplicações.

---

## 🗃️ Banco de Dados

### ✅ Suporte ao banco:

- **MariaDB** para ambiente de produção com persistência relacional.

A seleção e configuração dos bancos são feitas via `application.properties`.

---

## ⚙️ Requisitos

- Java 21+
- Maven 3.8+
- Docker (opcional, para MariaDB)
- VS Code com Extension Pack for Java

---

## 📂 Estrutura do Projeto

```bash
com.example.demo
├── controller        # Camada Controller
├── model             # Entidades (Model)
├── repository        # Repositório MariaDB
├── service           # Lógica de Negócio
└── application.properties
