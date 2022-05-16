## Hello World Spring Batch

#### Resumo
- Foi usado o Spring Initializer and Maven para criar a estrutura básica do projeto
- As anotações @EnableBatchProcessing e @SpringBootApplication foram usadas para habilitar a utilização do Batch
- Foi criado um Spring Batch Job para imprimir "Hello world!" utilizando alguns componentes importantes como JobBuilderFactory, StepBuilderFactory e um banco de dados em memória (H2 Database)

#### Project creation (using STS4)
```
 New > Spring Starter Project
 Project Dependencies:
 - I/O: Spring Batch
 - SQL: H2 Database
```
- Full Url: [https://start.spring.io/starter.zip](https://start.spring.io/starter.zip?name=helloBatch&groupId=com.lab&artifactId=helloBatch&version=0.0.1-SNAPSHOT&description=Demo+project+for+Spring+Boot&packageName=com.example.demo&type=maven-project&packaging=jar&javaVersion=1.8&language=java&bootVersion=2.6.7&dependencies=batch&dependencies=h2)
