**ROTAS DOS SERVIÇOS**

POST -cadastro de usuario bancario - /bank/cad-user
<br/>
POST -cadastro de conta bancaria - /bank/cad-acc
<br/>
GET  -listar contas dos usuarios - /bank/get-user/:id
<br/>
GET  -listar contas bancarias de um usuario - /bank/get-acc/:id
<br/>
PUT  -editar usuario - /bank/edit-user
<br/>
PUT  -editar conta bancaria - /bank/edit-acc
<br/>
DELETE -deletar usuario - /bank/delete-user/:id
<br/>
DELETE -deletar conta bancaria - /bank/delete-acc/:id
<br/>
POST -depositar dinheiro em uma conta bancaria - /bank/deposit
<br/>
GET -puxar saldo  da conta - /bank/get-balance/:id
<br/>
POST -realizar transferencia bancaria - /bank/transfer
<br/>
GET  -ver transferencias realizadas de um usuário - /bank/get-transfer/:id
<br/>

**Tecnologias utilizadas**

NodeJS - Express
<br/>
TypeScript