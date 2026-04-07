# Sistema CRUD de Alunos e Professores - JavaFX + MySQL

## Descrição
Aplicação desktop desenvolvida para a disciplina **Desenvolvimento de Sistemas II**.  
O sistema permite o gerenciamento completo de alunos e professores de uma escola, com interface gráfica moderna utilizando **JavaFX** e persistência de dados em **MySQL**.

## Tecnologias utilizadas
- **Java 17**
- **JavaFX 17** (com FXML)
- **Maven** (gerenciador de dependências)
- **MySQL** (banco de dados)
- **JDBC** (conexão com o banco)
- **DAO Pattern**

## Funcionalidades
- **CRUD Alunos**: nome, email, sala, módulo, curso, data de nascimento, telefone e status (ativo)
- **CRUD Professores**: nome, matéria e período
- Interface com tabelas separadas
- Formulários modais para inclusão e edição
- Validações de campos obrigatórios
- Criação automática das tabelas no banco

## Pré-requisitos
- JDK 17 ou superior
- MySQL instalado e rodando
- Maven 3.8+

## Configuração do Banco de Dados

1. Crie o banco:
```sql
CREATE DATABASE escola CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
