# 👤 Person API - DIO Live Coding

Este projeto foi desenvolvido durante o **Bootcamp da Digital Innovation One (DIO)** com o objetivo de criar uma **API RESTful para gerenciamento de pessoas** utilizando **Spring Boot**.

A aplicação permite realizar operações de **CRUD (Create, Read, Update, Delete)** em registros de pessoas, aplicando boas práticas de arquitetura e desenvolvimento com Java moderno.

---

## 🚀 Tecnologias Utilizadas

- **Java 21**
- **Spring Boot 3+**
- **Maven**
- **Lombok**
- **MapStruct**
- **H2 Database**
- **Postman / Insomnia** (para testes da API)

---

## 🧠 Conceitos Aplicados

- Arquitetura em camadas (Controller, Service, Repository)  
- Uso de **DTOs** para transferência de dados  
- Mapeamento automático com **MapStruct**  
- Injeção de dependências com **Spring Boot**  
- Tratamento de exceções personalizadas  
- Banco de dados em memória (**H2**) para desenvolvimento e testes  

---

## 🔗 Endpoints Principais

| Método | Endpoint              | Descrição                        |
|--------|------------------------|----------------------------------|
| `POST` | `/api/v1/people`       | Cadastra uma nova pessoa         |
| `GET`  | `/api/v1/people`       | Lista todas as pessoas           |
| `GET`  | `/api/v1/people/{id}`  | Busca uma pessoa por ID          |
| `PUT`  | `/api/v1/people/{id}`  | Atualiza uma pessoa existente    |
| `DELETE` | `/api/v1/people/{id}`| Remove uma pessoa do sistema     |

---

## ⚙️ Como Executar o Projeto

### Pré-requisitos
- Java 21 instalado  
- Maven configurado  
- IDE de sua preferência (IntelliJ, Eclipse, VS Code, etc.)

### Passos para execução
```bash
# Clonar o repositório
git clone https://github.com/davidMarostica/personapi_dio_live_coding.git

# Acessar o diretório do projeto
cd personapi_dio_live_coding

# Compilar e executar o projeto
mvn spring-boot:run
