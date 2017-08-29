# ANGULAR4-LITE-SERVER
Angular 4 APP with server-lite

- CREAR APP DIRECTORIO:

mkdir ANGULAR4

- CREAR INDEX.HTML

touch index.html

- CREAR PACKAGE.JSON

npm init -yes

- INSTALAR LITE-SERVER

npm install lite-server —save-dev

- ARRANCAR SERVIDOR

npm run lite

- INSTALA TYPESCRIPT

npm install —save-dev typescript typings

- CREAR CONFIGS DE TYPESCRIPT

touch tsconfig.json typings.json

- DESPUÉS DE MODIFICAR  TSCONFIG.JSON INSTALAR TYPINGS

npm install -g typings

- INSTALAR DEPENDECNIAS DE TYPINGS

typings install dt~core-js dt~jasmine dt~node --save --global

- CORRER TYPESCRIPT Y TYPINGS AL MISMO TIEMPO

npm install concurrently --save-dev
