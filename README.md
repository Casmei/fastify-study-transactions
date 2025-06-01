
# Transactions API
Uma API simples em Node.js para gerenciar transações (crédito/débito) usando Fastify, Knex e SQLite. Inclui testes automatizados com Vitest e Supertest.


## Visão Geral
- Endpoints para criar, listar, obter e resumir transações.
- Armazena dados em banco SQLite (via Knex).
- Utiliza cookies para rastrear sessões de usuário.
- Testes cobrindo rotas principais.

  
### Testes:
Para rodar os testes de integração: `npm test`


### Migrações :
Aplicar migrações: `npm run knex migrate:latest`<br/>
Reverter migrações: `npm run knex migrate:rollback --all`

Feito com amor e café ☕❤️
