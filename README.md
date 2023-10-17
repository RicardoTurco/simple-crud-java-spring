# simple-crud-java-spring
Exemplo de CRUD utilizando Java e Spring

## IMPORTANTE:
```
Antes de executar o projeto, é necessário rodar o 'docker-compose' para que 
o banco de dados 'Postgres' e o 'PgAdmin' estejam disponíveis:

- docker-compose up -d
```

## Executando o projeto:
```
Para executar o projeto é necessário instalar as dependências do projeto (Maven),
seja via terminal ou via IDE.

Via Terminal:

- mvn clean
- mvn install

Via IDE:

- clicar na seção 'Maven'
- clicar em 'clean' e depois em 'Run Maven Build'
- clicar em 'install' e depois em 'Run Maven Build'

Caso ocorra algum erro ao instalar as dependências, verique no arquivo
'src/main/resources/application.properties' se as credenciais 
do banco Postgres (url, username e password) estão IGUAIS as definidas 
no arquivo 'docker-compose.yml'. 
```
