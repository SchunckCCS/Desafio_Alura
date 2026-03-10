# Alura SQL Challenge — Disciplines Query

Projeto desenvolvido como parte de um desafio prático da **Alura** para praticar consultas em **SQL** e manipulação de dados em tabelas relacionais.

O desafio consiste em trabalhar com uma tabela de disciplinas e realizar consultas utilizando filtros e condições.

---

# Estrutura do Projeto

```
.
├── Desafio_alura_part1.xlsx
├── Desafio_alura_part2.xlsx
└── README.md
```

---

# Estrutura da Tabela

Tabela utilizada no desafio: **Disciplinas**

| Coluna             | Descrição                   |
| ------------------ | --------------------------- |
| id_disc            | Identificador da disciplina |
| nome_disc          | Nome da disciplina          |
| descricao_disc     | Descrição da disciplina     |
| carga_horaria_disc | Carga horária da disciplina |
| id_prof            | Identificador do professor  |

---

# Consulta SQL Utilizada

```sql
SELECT *
FROM Disciplinas
WHERE carga_horaria_disc > 40;
```

### Explicação

Essa consulta:

* Seleciona todas as colunas da tabela `Disciplinas`
* Filtra apenas disciplinas cuja **carga horária seja maior que 40 horas**

---

# Objetivo do Desafio

Praticar conceitos fundamentais de **Banco de Dados**, incluindo:

* Estrutura de tabelas relacionais
* Consultas com `SELECT`
* Uso de `WHERE`
* Filtragem de dados
* Organização de dados em SQL

---

# Tecnologias Utilizadas

* SQL
* Excel
* Conceitos de Banco de Dados Relacional

---

# Autor

Desenvolvido por **Cauã Schunck**
Estudante de **Ciência da Computação**
