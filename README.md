# Prática: Testes Unitários e Mocking em Spring Boot

## Objetivo

Este projeto tem como objetivo a implementação e validação de testes unitários para um controlador de usuários em uma aplicação Spring Boot. Através do uso de JUnit 5 e Mockito, os testes simulam comportamentos e validam o funcionamento correto dos endpoints da aplicação.

---

## Tecnologias Utilizadas

- Java 11+
- Spring Boot
- Spring Web
- Spring Data JPA
- MariaDB
- JUnit 5
- Mockito
- Spring Boot DevTools

---

## Estrutura do Projeto

- `controller/`: Contém o controlador de usuários.
- `service/`: Camada de serviço responsável pela lógica de negócio.
- `repository/`: Interface de persistência com Spring Data JPA.
- `model/`: Entidades do sistema.
- `test/`: Pacote com os testes unitários implementados com JUnit e Mockito.

---

## Como Executar

### Pré-requisitos

- Java 11 ou superior instalado
- MariaDB configurado e rodando
- IDE compatível com Spring Boot (como IntelliJ ou Eclipse)

### Passos

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
spring.datasource.url=jdbc:mariadb://localhost:3306/seu_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha

Execute a aplicação pela IDE ou com o comando:

bash
Copiar
Editar
./mvnw spring-boot:run
Para rodar os testes, use:

bash
Copiar
Editar
./mvnw test

Testes
Os testes unitários estão localizados no diretório src/test/java.

Utilizamos Mockito para mockar dependências e simular comportamentos.

Utilizamos JUnit 5 para estruturar e executar os testes.

Resultado
Todos os testes foram executados com sucesso. Caso ocorra alguma falha, a mensagem de erro ajudará a identificar rapidamente o ponto a ser corrigido no código.
