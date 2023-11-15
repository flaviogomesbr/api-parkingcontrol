## api estacionamento de um condomínio

<div align="center">
    <h1>
    <img width=150 src='https://s2-techtudo.glbimg.com/twoewJmwpMgtGPcRPP8SxFlDVmM=/0x0:695x393/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_08fbf48bc0524877943fe86e43087e7a/internal_photos/bs/2021/P/f/y52r4ySZWLkJjEhKLhgw/2014-11-14-java-logo.jpg'>
    <img width=150 src='https://www.qindel.com/wp-content/uploads/2023/04/spring-boot.jpeg'>
    </h1>
</div>

## Sobre

API em Java (Spring Boot) com CRUD simulando o estacionamento de um condomínio, com suas regras e validações básicas, apresentada no tutorial [Spring Boot | Curso Completo 2022](https://www.youtube.com/watch?v=LXRU-Z36GEU&t=1594s).

## Funcionalidades e requisitos da API

**Tecnologias e linguagens de programação**

- Java 17 ou 21;
- Spring Boot;
- MySQL;

**Operações que a aplicação deverá permitir**

- As quatro operações de um CRUD básico: CREATE (CRIAR), READ (LER), UPDATE (ALTERAR) e DELETE (EXCLUIR). Base do Spring Framework, Inversão de Controle, Injeção de Dependências, Beans, definição Spring Boot e também a construção de um projeto Spring Boot (Parking Control API) do zero, com projetos como Spring MVC, Spring Data JPA e Spring Validation para a criação de uma API com Pageable, métodos getAll, getOne, post, delete, update e Global Custom Date.


## Preparação do ambiente
- [IDE Java IntelliJ ou equivalente técnico](https://www.jetbrains.com/pt-br/idea/) <br>
- [Java JDK 17](https://www.oracle.com/br/java/technologies/downloads/#java17) <br>
- [Maven](https://maven.apache.org/) <br>
- [MySQL Community Server 8.0.35](https://dev.mysql.com/downloads/mysql/) <br>
- [MySQL Workbench 8.0.34](https://dev.mysql.com/downloads/workbench/) <br>
- [Post Man ou equivalente técnico](https://www.postman.com/downloads/) <br>

## Executando o projeto

Garantir a instalação dos itens listados anteriormente em "Preparação do ambiente";

Clonar este projeto para a sua máquina e executar o seguinte comando dentro do MySQL WorkBench (ou outro software equivalente técnico):

```sh
create database parking_control_db;
```

Abrir e executar o projeto dentro da IDE IntelliJ (ou outro software equivalente técnico);

Dentro do software Postman, importar a seguinte collection da raiz do projeto:

`00_MELI_JavaSpringBoot_API_parking-Spot.postman_collection`

Executar as requisições do CRUD, iniciando pelo POST.

Para consultar os registros no banco de dados, dentro do MySQL Workbench, digitar o seguinte comando:

```sh
SELECT * FROM parking_control_db.tb_parking_spot;
```

**License**

[MIT](https://tldrlegal.com/license/mit-license)
