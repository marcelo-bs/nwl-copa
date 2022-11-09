# Notas de estudo
## Servidor

Pasta *server* é o backend da aplicação.

### Comandos usados

Para criar servidor, não foi usdo express devido este framework ser mais leve e outros benefícios
```
npm i fastify
``` 


Automatizador para trascrever o ts para js. Config efetuada na prop **script** do **package.json**.
```
npm i tsx -D
```


Ferramenta para gerenciar banco de dados durante o desenvolvimento
```
npm i prisma -D
```


Client do banco de dados *prisma*
```
npm i @prisma/client
```


Criando banco com sqlite
```
npx prisma init --datasource-provider SQLite
```


Criação de *migrate* do banco de dados, rodar a cada mudança do banco (versão)
```
npx prisma migrate dev
```


Visualização do banco de dados
```
npx prisma studio
```


Dependencias criação de diagrama entidade/relacionamento
```
npm i prisma-erd-generator @mermaid-js/mermaid-cli -D
```


Gerar diagrama de entidade/relacionamento
```
npx prisma generate
```


Popular banco com seed
```
npx prisma db seed
```


Cors
```
npm i @fastify/cors
```

## Front

Front end da aplicação


### Comandos usados


Instalação do next js
```
npx create-next-app@latest --use-npm
```


## Mobile

React-native, emulador e ambiente


### Comandos usados

Para instalação do expo seguir os passos em: https://react-native.rocketseat.dev/expo-managed/linux


Criando aplicativo com expo
```
npx create-expo-app nwlCopaMobile
```