# Projeto Spring Boot com Maven

Este é um projeto Spring Boot utilizando Maven como ferramenta de gerenciamento de dependências e construção. O projeto também inclui o Spring Boot Actuator para fornecer funcionalidades prontas para produção, como métricas e health checks.

## Como executar o projeto:

1. Navegue até o diretório raiz do projeto.
2. Execute o seguinte comando via terminal:

```bash
mvn spring-boot:run
```
Após executar o comando, a aplicação será iniciada.

## Verificando o Health Check
Veja se a aplicação esta em rodando verificando o status de saúde da aplicação, acesse o seguinte link no seu navegador:

http://localhost:8080/actuator/health

Isso retornará o status de saúde da sua aplicação (UP indica que está tudo bem) ou DOWN.