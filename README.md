# 📘 Plano de Aula – Sistema de Biblioteca (Modelagem e Implementação de Banco de Dados Relacional)

## 🧑‍🏫 Professor: Cristian Ramos  
**Projeto Pedagógico:** Sistema de biblioteca para ensino de modelagem e prática com SQL  
**Área:** Banco de Dados / Análise de Sistemas / Informática  
**Público-Alvo:** Estudantes de cursos técnicos ou graduação em TI  
**Carga Horária Recomendada:** 4 a 6 aulas de 1h30 (ou conforme cronograma da disciplina)

---

## 🎯 Objetivos da Aula

### Objetivo Geral:
Capacitar o aluno a modelar e implementar um banco de dados relacional completo, com foco na estrutura de uma biblioteca, utilizando boas práticas de normalização, relacionamento entre tabelas e execução de consultas SQL.

### Objetivos Específicos:
- Desenvolver o modelo conceitual (MER) e lógico (DER) de um sistema de biblioteca.
- Criar tabelas com chaves primárias e estrangeiras em MySQL.
- Realizar consultas SQL envolvendo múltiplas tabelas e relacionamentos.
- Utilizar funções agregadas, subqueries, views e procedures simples.
- Aplicar o conhecimento de forma prática com foco em cenários reais.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- MySQL Server
- MySQL Workbench
- SQL Script (DDL, DML e DQL)
- (Opcional) DBDesigner, Draw.io ou Lucidchart para modelagem
- Editor de texto ou IDE com suporte a SQL

---

## 📚 Conteúdos Trabalhados

- Modelagem Conceitual (MER) e Lógica (DER)
- Normalização de dados (1FN, 2FN, 3FN)
- Criação de tabelas com `PRIMARY KEY`, `FOREIGN KEY`
- Comandos SQL:
  - `CREATE`, `INSERT`, `SELECT`, `UPDATE`, `DELETE`
  - `JOIN`, `GROUP BY`, `ORDER BY`, `HAVING`
  - Funções agregadas: `COUNT()`, `AVG()`, `SUM()`
  - Subqueries
  - Views
  - Procedures simples

---

## 📅 Cronograma Sugerido

### 🟩 Aula 1 – Introdução e Modelagem
- Apresentação do projeto “Sistema de Biblioteca”
- Levantamento de requisitos: usuários, livros, empréstimos, reservas
- Modelagem do MER com entidades e relacionamentos
- Conversão para o DER com chaves primárias e estrangeiras

> **Atividade:** Criar o MER e DER da biblioteca usando papel ou ferramenta digital.

---

### 🟨 Aula 2 – Criação do Banco e Tabelas
- Introdução ao MySQL Workbench
- Criação do banco de dados e tabelas com `CREATE TABLE`
- Aplicação de `NOT NULL`, `AUTO_INCREMENT`, `FOREIGN KEY`
- Inserção de dados fictícios com `INSERT INTO`

> **Atividade:** Criar todas as tabelas com base no DER e alimentar com dados iniciais.

---

### 🟥 Aula 3 – Consultas Básicas e JOINs
- Comando `SELECT` com filtros (`WHERE`)
- JOINs entre tabelas (INNER, LEFT, RIGHT)
- Exemplos: listar livros emprestados, livros por categoria, histórico de um leitor

> **Atividade:** Criar 5 consultas com `JOIN`, `ORDER BY` e `GROUP BY`.

---

### 🟦 Aula 4 – Funções Agregadas, Views e Subqueries
- Aplicação de `COUNT()`, `AVG()`, `SUM()`, `MAX()`, `MIN()`
- Criação de views para relatórios reutilizáveis
- Subqueries (correlacionadas ou não)
- Introdução a `CREATE PROCEDURE` e `CALL`

> **Atividade:** Criar uma view com dados consolidados e uma procedure simples de consulta.

---

## 🧠 Competências Desenvolvidas

- Análise e modelagem de sistemas de informação
- Criação e manutenção de banco de dados relacionais
- Escrita de comandos SQL complexos e estruturados
- Raciocínio lógico aplicado à estrutura de dados
- Interpretação de cenários reais e abstração para banco de dados

---

## ✅ Avaliação

| Critério                          | Peso |
|-----------------------------------|------|
| Qualidade da modelagem MER/DER    | 25%  |
| Criação correta das tabelas       | 20%  |
| Eficiência e clareza das consultas| 25%  |
| Uso correto de views e subqueries | 20%  |
| Participação nas atividades       | 10%  |

---

## 💡 Recursos Didáticos

- Slides explicativos sobre modelagem e SQL
- Exemplos prontos de outros sistemas (loja, escola)
- Acesso ao MySQL Workbench
- Guia de comandos SQL (folha de apoio ou cheat sheet)

---

> Este projeto foi desenvolvido com finalidade didática para ensinar a construção de bancos de dados relacionais usando como base um sistema de biblioteca escolar/universitária. Ele pode ser expandido com sistemas de login, interface gráfica ou integração com front-end futuramente.

```
