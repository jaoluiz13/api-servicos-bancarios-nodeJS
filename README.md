**ROTAS DOS SERVIÇOS**


[POST] - Cadastro de usuário bancário - /bank/cad-user
<br/>

[POST] - Cadastro de conta bancária - /bank/cad-acc
<br/>

`{Cada Usuário terá apenas uma conta bancaria vinculada ao seu CPF}`

[GET]  - Listar contas dos usuários - /bank/get-user/:id
<br/>

[PUT]  - Editar usuário - /bank/edit-user
<br/>
[PUT]  - Editar conta bancária - /bank/edit-acc
<br/>
[DELETE] - Deletar usuário - /bank/delete-user/:id
<br/>
[DELETE] - Deletar conta bancária - /bank/delete-acc/:id
<br/>
`{Só é possível deletar um usuário se não existir contas vinculadas a ele}`

[POST] - Depositar dinheiro em uma conta bancária - /bank/deposit
<br/>
[GET] - Buscar saldo  da conta - /bank/get-balance/:id
<br/>

**Toda parte de transferências bancárias será realizada por um micro-serviço que terá um serviço de fila.**

**Tecnologias utilizadas**

NodeJS - Express
<br/>
TypeScript
<br/>
Kafka
<br/>
MongoDB
