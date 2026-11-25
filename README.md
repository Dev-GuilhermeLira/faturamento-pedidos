# Faturamento de Pedidos

Atividade 03 da disciplina **Java II — Tópicos Avançados**, da Pós-Graduação em Desenvolvimento Java.

Sistema de **faturamento de pedidos** desenvolvido com foco em orientação a objetos e boas práticas de projeto, buscando um código fácil de manter, reutilizar e estender, com **baixo acoplamento**.

## 🧠 Conceitos aplicados

- Programação Orientada a Objetos
- Separação de responsabilidades
- Encapsulamento
- Interfaces e polimorfismo
- Composição
- Tratamento de diferentes comportamentos por meio de abstrações
- Princípios **SOLID**
- **Pattern Matching**, quando aplicável
- Testes automatizados
- Gerenciamento de dependências e execução dos testes com Maven

## 🏛️ Princípios SOLID

| Princípio | Conceito |
|---|---|
| **S — Single Responsibility Principle** | Uma classe deve possuir uma responsabilidade bem definida. |
| **O — Open/Closed Principle** | O código deve estar aberto para extensão e fechado para modificações desnecessárias. |
| **L — Liskov Substitution Principle** | Subtipos devem poder substituir seus tipos base sem quebrar o comportamento esperado. |
| **I — Interface Segregation Principle** | Interfaces devem ser específicas e não obrigar classes a implementar métodos que não utilizam. |
| **D — Dependency Inversion Principle** | O código deve depender de abstrações, e não diretamente de implementações concretas. |

Aplicar esses princípios deixa o código preparado para receber novas regras de negócio sem exigir alterações excessivas nas funcionalidades existentes.

## 🛠️ Tecnologias

Java · Maven · JUnit · IntelliJ IDEA · Git · GitHub

## 🗂️ Estrutura do projeto

```text
.
├── src/
├── pom.xml
└── README.md
```

## ▶️ Como executar

O projeto pode ser aberto no **IntelliJ IDEA** como projeto Maven, ou executado pelo Maven Wrapper.

Executar os testes:

```bash
# Windows
mvnw.cmd test

# Linux / macOS
./mvnw test
```

Compilar o projeto:

```bash
# Windows
mvnw.cmd clean package

# Linux / macOS
./mvnw clean package
```

Os diretórios `target/` e os arquivos da IDE não são versionados, conforme o `.gitignore`.

## 🎯 Objetivo acadêmico

Praticar **orientação a objetos** e **SOLID** em um cenário de negócio, construindo uma solução organizada e preparada para evoluir.

Este repositório faz parte do portfólio acadêmico da Pós-Graduação em Desenvolvimento Java.
