<p align="center">
  <img  src="./assets/Node.js_logo.svg">
</p>

# Módulo 2 - 'Primeiro Projeto com NodeJS' do Bootcamp GoStack da Rocketseat - 2020

:rocket: Projeto desenvolvido para estudo de Back-end com princípios SOLID e utilizando os conceitos de models, repositories e services!

## Dependências e libs

* yarn
      yarn init -y
* Express
      yarn add express
* TypeScript
      yarn add typescript -D
      yarn tsc --init (gera o arquivo tsconfig.json)

* Types do Express
      yarn add @types/express -D

* ts-node-dev
      yarn add ts-node-dev -D
Executa projeto com typescript e Node
Faz o papel do tsc pois, converte typescript para javascript e do nodemon, pois faz a atualização do código de forma automática.
Substitui nodemon, tsc watch, sucraze, etc;

* Para executar o servidor
      yarn dev:server

* package.json
      --transpile-only (desabilita a checagem do código)
      --ignore-watch node_modules (evita q o ts-node-dev tente compilar códigos do node_modules)

* import/export
      yarn add eslint-import-resolver-typescript -D (para habilitar import/export)

* UUIDV4
      yarn add uuidv4
Criação de id

* date-fns
      yarn add date-fns
Para validar datas

### Rotas da aplicação

- **`POST /appointments`**: A rota deve receber `id`, `provider` e `date` dentro do corpo da requisição.

- **`GET /appointments`**: Rota que lista todos os agendamentos.

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Finalizado
