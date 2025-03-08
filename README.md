# REST API com Spring Boot e Frontend em React

![Badge](https://img.shields.io/badge/Status-%20Concluído-green) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2.7-brightgreen) ![React](https://img.shields.io/badge/React-18.3.1-blue)

Este projeto consiste em uma API REST desenvolvida com **Spring Boot** integrada a um frontend em **React**, seguindo as melhores práticas para construção de aplicações modernas e escaláveis.

## 🚀 Tecnologias Utilizadas

### Backend:
- **Java 8+**
- **Spring Boot 3.2.7**
- **Spring Data JPA**
- **Hibernate**
- **MySQL**
- **Spring Security**
- **Swagger (OpenAPI)**
- **Maven**

### Frontend:
- **React 18.3.1**
- **Create React App (`react-scripts`)**
- **Axios**
- **React Router DOM 6.24.1**
- **React Icons**

## 📌 Funcionalidades

- 🌐 **CRUD completo de usuários**
- 🔑 **Autenticação e Autorização com JWT**
- 📄 **Documentação com Swagger/OpenAPI**
- 📊 **Integração entre Spring Boot e React**
- 🚀 **Desenvolvimento Full-Stack simplificado**

## 🎯 Como Executar o Projeto

### 📌 Pré-requisitos
Antes de iniciar, você precisará ter instalado:
- Java 8+
- Node.js + npm/yarn
- MySQL

### 🔧 Passos para execução
#### 🔹 Backend (Spring Boot)
1. Clone o repositório:
   ```sh
   git clone https://github.com/EltonRiva1/RestWithSpringBootUdemyFiles-React.git
   ```
2. Acesse a pasta do backend:
   ```sh
   cd RestWithSpringBootUdemyFiles-React/server
   ```
3. Configure o banco de dados no arquivo `application.yml`:
   ```yaml
   spring:
     datasource:
       driver-class-name: com.mysql.cj.jdbc.Driver
       url: jdbc:mysql://localhost:3306/rest_with_spring_boot?useTimezone=true&serverTimezone=UTC
       username: root
       password: root
     jpa:
       hibernate:
         ddl-auto: update
   ```
4. Compile e execute o backend:
   ```sh
   mvn spring-boot:run
   ```
5. Acesse a API no navegador ou via Postman:
   ```
   http://localhost:8080/api
   ```
6. Para visualizar a documentação da API (Swagger):
   ```
   http://localhost:8080/swagger-ui.html
   ```

#### 🔹 Frontend (React)
1. Acesse a pasta do frontend:
   ```sh
   cd ../client
   ```
2. Instale as dependências:
   ```sh
   npm install
   ```
3. Inicie o frontend:
   ```sh
   npm start
   ```
4. Acesse a aplicação no navegador:
   ```
   http://localhost:3000
   ```

## 🛠️ Contribuindo
1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature-minha-feature`)
3. Commit suas alterações (`git commit -m 'Adicionando nova funcionalidade'`)
4. Faça um push para a branch (`git push origin feature-minha-feature`)
5. Abra um Pull Request

---

🔹 Desenvolvido por [Elton Riva](https://github.com/EltonRiva1) 🚀

