## Projeto Gobarber-V2
  Refiz o projeto para fixar o conhecimento.

  App para agedamendo de serviços de cabeleireiro.

## Requisitos

  node.js
  NPM
  Yarn

## Databases

  Postgres
  Mongo
  Regis

  Ps: Use o docker para rodar as imagens dos dbs.

## Instruções

  "yarn" na raiz do projeto para istalar todas as dependencias.

  "yarn dev" para executar o projeto.

  "yarn queue" para executar fila de jobs em background.


## Rotas

  BASE_URL = http://localhost:3003

  POST 'BASE_URL/users', Cria um usuário.

  POST 'BASE_URL/sessions', Autêntica o usuário usando o Jsonwebtoken(JWT).

  PUT 'BASE_URL/users', Atualiza o usuário.

  GET 'BASE_URL/providers', Retorna lista de prestadores de serviço.

  GET 'BASE_URL/providers/:providerId/available', Retorna os horários disponiveis para agendar um serviço.

  POST 'BASE_URL/appointments', Cria um agendamento.

  GET 'BASE_URL/appointments', Retorna os agendamentos.

  DELETE 'BASE_URL/appointments/:id', Deleta um agendamento pelo id.

  GET 'BASE_URL/schedule', Lista a agenda de agendamentos do prestador no dia.

  GET 'BASE_URL/notifications', Retorna as notificações.

  PUT 'BASE_URL/notifications/:id', Marca a notificação como lida.
