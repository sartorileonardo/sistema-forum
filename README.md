# Tópicos

O sistema permite ao usuário consultar, alterar e remover tópicos.
Foi desenvolvido com objetivo de aprendizado no curso [Spring Boot-Cache-Segurança-Monitoramtento](https://cursos.alura.com.br/course/spring-boot-seguranca-cache-monitoramento) da Alura.

## Tecnologias/Configurações aplicadas
- Spring Boot;
- JPA;
- H2 Database;
- Cache;
- Paginator;
- Actuator;
- Autenticação JWT;
- Swagger Documentation;

## Execução

Para clonar a rodar o projeto, use:

```bash
git clone https://github.com/sartorileonardo/sistema-forum;
cd sistema-forum
mvn spring-boot:run
```

## Execução com Docker
```bash
docker build -t alura/forum .
docker run -p 8080:8080 -e FORUM_DATABASE_URL='jdbc:h2:mem:alura-forum' -e FORUM_DATABASE_USERNAME='sa' -e FORUM_DATABASE_PASSWORD='' -e FORUM_JWT_SECRET='123456' alura/forum
```

## Documentação de API

Após clonar e executar o projeto, acesse [Swagger Documentation API](http://localhost:8080/swagger-ui.html#/)


## Licença de software
[MIT](https://choosealicense.com/licenses/mit/)
