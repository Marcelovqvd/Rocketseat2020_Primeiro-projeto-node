# Estudo de NodeJS com TypeScript

yarn init -y
yarn add express
yarn add typescript -D
yarn tsc --init (gera o arquivo tsconfig.json)
yarn add @types/express -D

ts-node-dev
yarn add ts-node-dev -D
Executa projeto com typescript e Node
Faz o papel do tsc pois, converte typescript para javascript e do nodemon, pois faz a atualização do código de forma automática.
Substitui nodemon, tsc watch, sucraze, etc;

yarn dev:server para executar o servidor

--transpile-only (desabilita a checagem do código)
--ignore-watch node_modules (evita q o ts-node-dev tente compilar códigos do node_modules)

yarn add eslint-import-resolver-typescript -D (para habilitar import/export)

uuidv4 para formar id
yarn add uuidv4

