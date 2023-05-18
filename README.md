# RESTful API de Usuários

[![Hcode Treinamentos](https://www.hcode.com.br/res/img/hcode-200x100.png)](https://www.hcode.com.br)

API desenvolvida em Node.js para o Curso Completo de JavaScript na Udemy.com.

### Projeto Vulpo instaladno o express: npm install express --save
### Projeto Vulpo instaladno o nodemon: npm install nodemon -g
### Projeto Vulpo para executar no gitbash nodemon index
### Projeto Vulpo instalando o consign: npm install consign --save
### Projeto Vulpo instalando o body-parse: npm install body-parser --save
### Projeto Vulpo instalando o nedb(banco de dados): npm install nedb --save
### Projeto Vulpo instalando o validator: npm install validator --save 
 
### Instalação
```
npm install
```

### Excutando servidor
```
npm start
```
## Rotas
Obter todos os usuários:
```
GET /users
```
Exemplo de resultado:
```json
{
    "users":[]
}
```

Cadastrar um novo usuário:
```
POST /users
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324",
    "name":"João Rangel"
}
```

Obter dados de um usuário:
```
GET /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324",
    "name":"João Rangel"
}
```

Editar um usuário:
```
PUT /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324"
}
```

Excluir um usuário:
```
DELETE /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324"
}
```