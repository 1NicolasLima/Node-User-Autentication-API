API REST

A ideia é:
Criar uma API de autenticação de usuário.

1- Aplicações clientes manda Login no sistema.
2- Volta um token JWT de autenticação do MS(Microserviço) de autenticação.
3- MS de produtos - Token Válido?
4- o MS de autenticação vai dizer se SIM ou se NÃO.


CRUD de Usuários

- GET /users  - Todos os usuários
- GET /users:uuid - Usuário específico
- POST /users - Incersão de um novo usuário
- PUT /users/:uuid - Alteração de um usuário
- DELETE /users/:uuid - Deletação de um usuário

Autenticação:
- POST /token - Obtenção de token.
- POST /token/validate - Operação para validar o token.