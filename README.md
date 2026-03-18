<div align="center">

# Willames Barbosa

**Desenvolvedor Back-End** · Node.js · PostgreSQL · REST APIs

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/willamessilvab)
[![Gmail](https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:willamessilva1999@gmail.com)
[![GitHub](https://img.shields.io/badge/-GitHub-%23181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/willamesbarbosa)

</div>

---

## Sobre mim

Desenvolvedor back-end em transição de carreira, com foco em construir APIs robustas, testáveis e bem estruturadas.

Venho do mundo da gestão — anos liderando operações em varejo, resolvendo problemas sob pressão e tomando decisões com recursos limitados. Esse background moldou minha forma de escrever código: pragmático, responsável e orientado a resultado.
---

## Stack

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Knex](https://img.shields.io/badge/Knex.js-E16426?style=for-the-badge&logo=knex.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

---

## Projetos

### 🗂️ [Task Manager API](https://github.com/willamesbarbosa/task-manager-api)
API REST completa para gerenciamento de tarefas, construída com arquitetura em camadas (Controller → Service → Repository).

**O que tem dentro:**
- Autenticação JWT com refresh tokens armazenados no Redis, permitindo rotação e invalidação segura de sessões
- Arquitetura em camadas com separação clara de responsabilidades
- Testes automatizados com Jest e SQLite in-memory (isolamento por suite)
- Logging estruturado com Pino — redação de tokens sensíveis, ambiente-aware
- PostgreSQL em produção via Docker · Migrações com Knex
- Conventional Commits · Feature branches

**Stack:** Node.js · Express · PostgreSQL · Redis · Jest · Knex · Docker · Pino

#### Decisões técnicas

- Optei por arquitetura em camadas para melhorar testabilidade e isolamento, mesmo aumentando a verbosidade no código
- Usei Redis para armazenar refresh tokens e permitir revogação imediata
- SQLite in-memory nos testes para garantir isolamento e velocidade
- Pino para logging estruturado e melhor observabilidade

#### Confiabilidade e tratamento de erros

- Middleware global de tratamento de erros para padronizar respostas da API
- Separação entre erros operacionais e inesperados
- Respostas consistentes (status codes + mensagens previsíveis)
- Evita vazamento de detalhes internos em produção

#### Problemas que resolvi

- Evitei inconsistência de respostas criando um padrão global de erros
- Implementei rotação de refresh tokens para reduzir risco de sessão comprometida
- Garanti isolamento total nos testes usando banco em memória
---

### 🧮 [Factor Calculator](https://github.com/willamesbarbosa/factor-calculator)
Calculadora desenvolvida para resolver uma dor real do meu time de vendas no varejo. Hoje é usada no dia a dia por colegas de trabalho.

Esse projeto representa algo importante pra mim: código que resolve problema real, não só exercício.

---

## Estatísticas

<div align="center">
  <img height="180em" width="35%" src="https://github-readme-stats.vercel.app/api?username=willamesbarbosa&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  <img height="180em" width="35%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=willamesbarbosa&layout=compact&langs_count=7&theme=dracula"/>
</div>

---

<div align="center">

*"Construindo uma base sólida, um commit de cada vez."*

</div>
