# Adform

A aplicação AdForm é um CRUD para inserção de usuários com alguns informações básicas e alguns tipos de endereços criada utilizando NodeJS e um container do Docker com Postgres para persistencia dos dados e o ReactJs para o frontend da aplicação.

Para melhor controle de versionamento a aplicação foi divida em dois repositórios:
- [adform-backend](https://github.com/brtrindade/adform-backend) : contento a API RESTful
- [adform-frontend](https://github.com/brtrindade/adform-frontend) : contento o frontend da aplicação

### Como utilizar:
É necessário ter instalado o NodeJS e o Docker com uma imagem do Postgres e seguir os passos indicados nos repositórios acima. A aplicação pode ser acessada por outros frontends, basta utilizar as rotas criadas na api do backend.
