# Desafio-KubeDev - Docker: Q4
Criado um .yaml para rodar com o docker-compose. 

Foi criado um Dockerfile no diretorio "/src" para criar a aplicação rotten-potatoes


## MongoDB

### Configuração

MONGO_TAG      => Para a versão da imagem do MongoDB (Utilizado a versão 4.4.12)

MONGO_USERNAME => Usuario para o MongoDB

MONGO_PASSWORD => Senha para o MongoDB 


## rotten-potatoes

### Configuração

MONGODB_DB => Nome do database (Não utilizado no docker-compose.yaml. Deixado a default[admin] da api)

MONGODB_HOST => Host do MongoDB

MONGODB_PORT => Posta de acesso ao MongoDB (Não utilizado no docker-compose.yaml. Deixado a default[27017] da api)

MONGODB_USERNAME => Usuário do MongoDB

MONGODB_PASSWORD => Senha do MongoDB
