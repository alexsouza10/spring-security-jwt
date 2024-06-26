# Spring Security JWT

Este projeto é uma aplicação Spring Boot que demonstra como implementar autenticação JSON Web Token (JWT) com Spring Security.

## Recursos

- **Autenticação JWT**: Usa JWT para autenticação de usuários, permitindo acesso seguro a recursos protegidos.
- **Gerenciamento de Usuários**: Fornece endpoints para criar novos usuários e fazer login.
- **Autorização Baseada em Função**: Suporta controle de acesso baseado em funções, permitindo diferentes níveis de acesso para diferentes funções de usuário.
- **Integração com Banco de Dados H2**: Utiliza um banco de dados H2 em memória para armazenar informações do usuário.

## Como Começar

Para executar este projeto localmente, siga estas etapas:

1. Clone o repositório em sua máquina local:

   ```bash
   git clone https://github.com/alexsouza10/spring-security-jwt.git

2. Navegue até o diretório do projeto.

3. Compile e execute a aplicação usando o Maven.

4. Acesse a aplicação em seu navegador da web em [http://localhost:8080](http://localhost:8080).

## Endpoints

- **POST /login**: Endpoint para autenticação de usuário. Requer um corpo JSON com os campos `username` e `password`.
- **POST /users**: Endpoint para criar um novo usuário. Requer um corpo JSON com informações do usuário.
- **GET /users**: Endpoint para recuperar informações sobre usuários autorizados.
- **GET /managers**: Endpoint para recuperar informações sobre gerentes autorizados.

## Configuração

O projeto usa as seguintes propriedades de configuração:

- **JWT Cripto Config**: Configuração para autenticação JWT, incluindo o prefixo do token, chave secreta e tempo de expiração.
- **Propriedades de Conexão do Banco de Dados H2**: Configuração para conexão com o banco de dados H2 em memória.

## Dependências

O projeto depende das seguintes bibliotecas:

- **Spring Boot Web**: Para construir aplicações web com Spring MVC.
- **Spring Data JPA**: Para acesso a dados usando a API de Persistência Java.
- **Spring Security**: Para implementar recursos de segurança, incluindo autenticação e autorização.
- **Banco de Dados H2**: Para armazenar informações do usuário em um banco de dados em memória.
- **JSON Web Token (JWT)**: Para gerar e validar tokens JSON Web.

## Contribuindo

Contribuições para este projeto são bem-vindas! Sinta-se à vontade para enviar problemas ou solicitações de recebimento para ajudar a melhorar a aplicação.
