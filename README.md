# Web Services Project with Spring Boot and JPA/Hibernate

This project is a web service application built using **Spring Boot**, **JPA/Hibernate**, and **Apache Tomcat**. The application interacts with a database and provides API endpoints for CRUD operations. 

## Features

- **Technologies used**: 
  - Spring Boot
  - Apache Tomcat
  - Maven
  - JPA/Hibernate
  - H2 Database
  - Postman for testing requests
- **Server Port**: 8080
- **Database**: H2 in-memory database (can be configured for other databases)
  
## Running the Project

### Requirements
- Java 17 or higher
- Maven 3.8+
- Postman (or any other API testing tool)

### How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/quadrado96/springboot-jpa.git
    ```
2. Navigate to the project directory:
    ```bash
    cd springboot-jpa
    ```
3. Build the project using Maven:
    ```bash
    mvn clean install
    ```
4. Run the project:
    ```bash
    mvn spring-boot:run
    ```
5. The application will run on `http://localhost:8080`.

### Testing the API
You can use **Postman** to test the API endpoints:
- Import the provided Postman collection from the `postman/` folder.
- Send requests to `http://localhost:8080` using the available endpoints for CRUD operations.

### Database Access
The application uses **H2** as an in-memory database by default. To access the H2 database console, go to:
- `http://localhost:8080/h2-console`
- Use the following credentials:
    - JDBC URL: `jdbc:h2:mem:testdb`
    - User: `sa`
    - Password: (leave empty)

## Course Reference
This project is based on the instructions provided in the [Java COMPLETO Programação Orientada a Objetos + Projetos](https://www.udemy.com/course/java-curso-completo/?couponCode=24T5MT100724) course by **Nélio Alves** on Udemy.


# Projeto de Web Services com Spring Boot e JPA/Hibernate

Este projeto é uma aplicação de serviço web construída utilizando **Spring Boot**, **JPA/Hibernate** e **Apache Tomcat**. A aplicação interage com um banco de dados e fornece endpoints de API para operações CRUD.

## Funcionalidades

- **Tecnologias utilizadas**:
  - Spring Boot
  - Apache Tomcat
  - Maven
  - JPA/Hibernate
  - Banco de dados H2
  - Postman para testar requisições
- **Porta do servidor**: 8080
- **Banco de dados**: Banco de dados H2 na memória (pode ser configurado para outros bancos de dados)

## Executando o Projeto

### Requisitos
- Java 17 ou superior
- Maven 3.8+
- Postman (ou qualquer outra ferramenta de teste de API)

### Como Executar
1. Clone o repositório:
    ```bash
    git clone https://github.com/quadrado96/springboot-jpa.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd springboot-jpa
    ```
3. Construa o projeto utilizando o Maven:
    ```bash
    mvn clean install
    ```
4. Execute o projeto:
    ```bash
    mvn spring-boot:run
    ```
5. A aplicação estará rodando em `http://localhost:8080`.

### Testando a API
Você pode usar o **Postman** para testar os endpoints da API:
- Importe a coleção Postman fornecida na pasta `postman/`.
- Envie requisições para `http://localhost:8080` utilizando os endpoints disponíveis para operações CRUD.

### Acesso ao Banco de Dados
A aplicação utiliza o banco de dados **H2** na memória por padrão. Para acessar o console do banco H2, acesse:
- `http://localhost:8080/h2-console`
- Use as seguintes credenciais:
    - URL JDBC: `jdbc:h2:mem:testdb`
    - Usuário: `sa`
    - Senha: (deixe em branco)

## Referência do Curso
Este projeto é baseado nas instruções fornecidas no curso [Java COMPLETO Programação Orientada a Objetos + Projetos](https://www.udemy.com/course/java-curso-completo/?couponCode=24T5MT100724) ministrado por **Nélio Alves** na Udemy.
