# Spring Boot — Fundamentos de API com Java

Projeto de estudo para explorar a estrutura de uma aplicação **Spring Boot** e a criação de endpoints HTTP em Java.

## Estado atual

- Aplicação Spring Boot configurada com **Maven**.
- Controller com rota de exemplo **`GET /users`**.
- Modelo `User` utilizado para retornar um objeto de exemplo.
- Dependências declaradas para **Spring Data JPA**, **H2** e **PostgreSQL**.

> Este repositório está nos **fundamentos**: a resposta atual do endpoint é estática. As dependências de persistência foram adicionadas, mas o projeto não deve ser apresentado como CRUD com banco de dados já implementado.

## Tecnologias

- **Java 25** (conforme `pom.xml`)
- **Spring Boot 4.0.6** (conforme `pom.xml`)
- Maven e Maven Wrapper
- Spring Web MVC
- Spring Data JPA (dependência de estudo)

## Executar

Com o **JDK 25** instalado, na raiz do repositório:

```bash
./mvnw spring-boot:run
```

No Windows:

```powershell
.\mvnw.cmd spring-boot:run
```

Depois, consulte `GET http://localhost:8080/users`.

## Próximos tópicos de estudo

- Implementar camada de serviço e repositório.
- Persistir entidades em um banco de dados.
- Adicionar validação, tratamento de erros e testes de endpoints.
- Revisar serialização e proteção de dados antes de qualquer uso real.

## Aviso

Este é um **exercício educacional**, com dados demonstrativos no código. Não foi construído para uso em produção nem como referência de autenticação ou proteção de dados sensíveis.

[Voltar ao perfil](https://github.com/Casapiccola)
