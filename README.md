# gobarber-api-node
API RESTful com NodeJS.

### Instalar dependências
yarn

###  Executar migrations
yarn sequelize db:migrate

####  Criar seeds
yarn sequelize seed:generate --name users

####  Executar todos os seeders
yarn sequelize db:seed:all

#### Desfaz todas as migrations
yarn sequelize db:migrate:undo:all

### Rodar projeto em modo de desenvolvimento
yarn dev
