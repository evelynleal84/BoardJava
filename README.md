
# 📝 Board de Tarefas em Java

Este projeto é um board de tarefas desenvolvido em **Java**, com persistência de dados em **MySQL**. Utiliza **Gradle** como gerenciador de dependências e segue boas práticas de arquitetura com separação de camadas, desde o planejamento até a implementação de funcionalidades como criação, listagem e atualização de tarefas.

---

## ✅ Etapas do Desenvolvimento

### 1. Planejamento
- Objetivo: gerenciar tarefas com título, descrição, status e data de criação.
- Tecnologias escolhidas: Java 17, Gradle, MySQL, JDBC, IntelliJ IDEA.

### 2. Estrutura do Projeto
- Organização em pacotes:
  - `config` → configuração de conexão com banco
  - `model` → entidades: Card, CardCollunm, Board e Block
  - `repository` → acesso aos dados (DAO)
  - `service` → lógica de negócio
  - `view` ou `main` → entrada da aplicação

### 3. Persistência com JDBC
- Conexão manual usando `DriverManager`.
- Criação da tabela `tarefas` com os campos essenciais.
- Manipulação de dados diretamente por SQL via código Java.

### 4. Funcionalidades Atuais
- Conexão com banco MySQL
- Criação automática da tabela
- Estrutura para CRUD (criar, ler, atualizar, deletar)

---

## 🔧 Tecnologias Utilizadas

- Java 17
- Gradle
- JDBC
- MySQL
- IntelliJ IDEA

---

## Diagrama do Projeto 

![Diagrama do Projeto](diagrama/board.png)

