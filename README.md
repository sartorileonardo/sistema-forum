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

## Execução do JAR com parâmetros
```bash
java -jar -DFORUM_DATABASE_URL=DATABASE:h2:
mem:alura-forum
-DFORUM_DATABASE_USERNAME=sa
-DFORUM_DATABASE_PASSWORD=
-DFORUM_JWT_SECRET=123456 forum.jar
```

## Documentação de API

Após clonar e executar o projeto, acesse [Swagger Documentation API](http://localhost:8080/swagger-ui.html#/)


## Licença de software
[MIT](https://choosealicense.com/licenses/mit/)
