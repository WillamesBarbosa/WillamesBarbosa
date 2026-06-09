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

Venho do mundo da gestão. Um bom tempo liderando decisões no varejo, resolvendo problemas sob pressão e tomando decisões com recursos limitados. Esse background moldou minha forma de escrever código: pragmático, responsável e orientado a resultado.

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
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)

</div>

---

## Projetos

### 🗂️ Kron — Task Manager

Sistema completo de gerenciamento de tarefas com kanban interativo. Backend e frontend em produção.

🔗 **[App ao vivo](https://kron-app.vercel.app)** · **[API](https://to-do-list-backend-production-edab.up.railway.app)** · **[Swagger](https://to-do-list-backend-production-edab.up.railway.app/docs)**

---

#### [Kron API — Backend](https://github.com/WillamesBarbosa/kron-api)

API REST completa construída com arquitetura em camadas (Controller → Service → Repository).

**O que tem dentro:**
- Autenticação JWT com refresh tokens armazenados no Redis, permitindo rotação e invalidação segura de sessões
- Arquitetura em camadas com separação clara de responsabilidades
- Testes automatizados com Jest e SQLite in-memory (isolamento por suite)
- Logging estruturado com Pino — redação de tokens sensíveis, ambiente-aware
- Rate limiting por rota com Redis como store persistente
- Soft delete com rastreamento de data de exclusão
- PostgreSQL em produção via Docker · Migrações com Knex
- Documentação interativa com Swagger
- Conventional Commits · Feature branches

**Stack:** Node.js · Express · PostgreSQL · Redis · Jest · Knex · Docker · Pino

#### Decisões técnicas

- Arquitetura em camadas para melhorar testabilidade e isolamento
- Redis para refresh tokens — revogação imediata no logout
- Rate limiting diferenciado por rota baseado no nível de risco
- SQLite in-memory nos testes para garantir isolamento e velocidade
- Pino para logging estruturado e melhor observabilidade

---

#### [Kron App — Frontend](https://github.com/WillamesBarbosa/kron-web)

Interface kanban com drag and drop e integração completa com a API.

**O que tem dentro:**
- Drag and drop entre colunas com atualização otimista
- Interceptor de refresh token automático — transparente pra toda a aplicação
- Gerenciamento de estado servidor com TanStack Query
- Proteção de rotas autenticadas
- Identidade visual própria com tema escuro

**Stack:** React · TypeScript · TanStack Query · dnd-kit · Tailwind · shadcn/ui · Vite

---

### 🧮 [Factor Calculator](https://github.com/willamesbarbosa/factor-calculator)
Calculadora desenvolvida para resolver uma dor real do meu time de vendas no varejo. Hoje é usada no dia a dia por colegas de trabalho.

Esse projeto representa algo importante pra mim: código que resolve problema real, não só exercício.

---

## Estatísticas

<div align="center">
  <img height="180em" src="https://github-readme-stats-blond-six-1vfifujd28.vercel.app/api?username=willamesbarbosa&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats-blond-six-1vfifujd28.vercel.app/api/top-langs/?username=willamesbarbosa&layout=compact&langs_count=7&theme=dracula"/>
</div>

---

<div align="center">

*"Construindo uma base sólida, um commit de cada vez."*

</div>
