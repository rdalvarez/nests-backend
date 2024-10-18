# Backend en Nest

1. Validar tener instaladas las siguientes dependencias

``` Node JS
npm i -g @nestjs/cli
```
``` Mongoose
npm i @nestjs/mongoose mongoose
```
``` Variables de Entorno
npm i @nestjs/config
```

2. Comando para ejecutar el archivo docker-compose.yml 
```
docker compose up -d
```
``-d `` es para que se ejecute de manera desenlazada de la terminal.

3. Copiar el ``.env.template`` y renombrarlo a ``.env``. 

4. Modificar la variable de entorno con el URI a la base de datos

5. Una vez levantado el *mongo-db*, inicializamos NestJs
```
npm run start:dev
```

