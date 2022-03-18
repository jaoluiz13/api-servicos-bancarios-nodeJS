**ROTAS DOS SERVIÇOS**

POST -cadastro de usuario bancario - /bank/cad-user
POST -cadastro de conta bancaria - /bank/cad-acc
GET  -listar contas dos usuarios - /bank/get-user/:id
GET  -listar contas bancarias de um usuario - /bank/get-acc/:id
PUT  -editar usuario - /bank/edit-user
PUT  -editar conta bancaria - /bank/edit-acc
DELETE -deletar usuario - /bank/delete-user
DELETE -deletar conta bancaria - /bank/delete-acc

POST -depositar dinheiro em uma conta bancaria - /bank/deposit
GET -puxar saldo  da conta - /bank/get-balance

POST -realizar transferencia bancaria - /bank/transfer
GET  -ver transferencias realizadas de um usuário - /bank/get-transfer

**Tecnologias utilizadas**

NodeJS - Express
TypeScript