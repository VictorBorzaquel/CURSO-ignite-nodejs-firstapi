yarn init -y = init node

tsc --init = iniciar typescript

tsconfig.json > "outDir": "./dist", 

tsc = convert to js

node dist/server.js  = init server

yarn add -D ts-node-dev
"scripts": {
    "dev": "ts-node-dev --inspect --transpile-only --ignore-watch node_modules --respawn src/server.ts"
  },

ESLINT

eslint --init

yarn add -D eslint-plugin-import-helpers eslint-import-resolver-typescript

create folder:

.eslintignore

```
/*.js
node_modules
dist
```

PRETTIER

yarn add prettier eslint-config-prettier eslint-plugin-prettier -D