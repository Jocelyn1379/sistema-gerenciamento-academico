# Sistema de Gerenciamento Acadêmico – SQL

Projeto de banco de dados relacional desenvolvido com MySQL para o gerenciamento de informações acadêmicas, incluindo alunos, professores, disciplinas, turmas e matrículas.

## Sobre o projeto

O projeto teve origem em uma atividade acadêmica e, posteriormente, foi revisado e aprimorado para fins de estudo e composição de portfólio.

Durante essa evolução, foram realizadas melhorias na estrutura do banco de dados, nos relacionamentos entre tabelas e nas consultas SQL, buscando aplicar conceitos importantes de modelagem e manipulação de dados relacionais.

## Tecnologias utilizadas

- **MySQL 8.3** – Sistema de gerenciamento de banco de dados.
- **SQL** – Linguagem utilizada para criação, manipulação e consulta dos dados.
- **MySQL Workbench 8.0** – Ferramenta para administração e execução dos comandos SQL.

## Estrutura do banco de dados

O banco de dados `sistema_academico` possui cinco tabelas principais:

| Tabela | Descrição |
|---|---|
| `aluno` | Armazena os dados dos alunos. |
| `professor` | Armazena os dados dos professores. |
| `disciplina` | Registra as disciplinas e suas cargas horárias. |
| `turma` | Relaciona disciplinas, professores e períodos letivos. |
| `matricula` | Registra as matrículas dos alunos nas turmas. |

As tabelas utilizam chaves primárias e estrangeiras para estabelecer relacionamentos e manter a integridade dos dados.

## Funcionalidades implementadas

- Criação do banco de dados e das tabelas.
- Definição de chaves primárias e estrangeiras.
- Aplicação de restrições de integridade, como `NOT NULL`, `UNIQUE` e `CHECK`.
- Inserção de dados fictícios para testes.
- Consultas utilizando `SELECT`, `WHERE` e `ORDER BY`.
- Relacionamento entre tabelas com `INNER JOIN` e `LEFT JOIN`.
- Agrupamento de informações com `GROUP BY` e `HAVING`.
- Utilização de funções de agregação, como `COUNT`.
- Criação de uma VIEW para geração de relatórios acadêmicos.

## Organização dos arquivos

```text
sistema-gerenciamento-academico/
│
├── 01_criacao_banco.sql
├── 02_criacao_tabelas.sql
├── 03_insercao_dados.sql
├── 04_consultas.sql
├── 05_views.sql
└── README.md
```

## Como executar o projeto

1. Instale o MySQL Server e o MySQL Workbench.
2. Abra o MySQL Workbench e conecte-se ao servidor.
3. Abra os arquivos SQL na ordem numérica indicada.
4. Execute cada arquivo seguindo a sequência:
   - `01_criacao_banco.sql`
   - `02_criacao_tabelas.sql`
   - `03_insercao_dados.sql`
   - `04_consultas.sql`
   - `05_views.sql`
5. Consulte os resultados das consultas e da VIEW criada.

**Observação:** os arquivos de criação e inserção devem ser executados em um banco preparado para receber os dados. Executar novamente o arquivo de inserção sem limpar os registros anteriores poderá gerar erros de chave duplicada.

## Aprendizados

O desenvolvimento e aprimoramento deste projeto permitiram praticar conceitos de:

- Modelagem de bancos de dados relacionais.
- Criação e relacionamento de tabelas.
- Integridade e consistência dos dados.
- Manipulação e consulta de informações com SQL.
- Construção de relatórios utilizando JOINs e VIEWs.

## Autor

**Jocelyn de Souza Pontes**

- GitHub: [Jocelyn1379](https://github.com/Jocelyn1379)
- LinkedIn: [Jocelyn Souza](https://www.linkedin.com/in/jocelyn-souza-dev)