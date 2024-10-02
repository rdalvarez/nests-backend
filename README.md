# Backend en Nest

Comando para ejecutar el archivo docker-compose.yml 
```
docker compose up -d
```
``-d `` es para que se ejecute de manera desenlazada de la terminal.

Copiar el ``.env.template`` y renombrarlo a ``.env``. 

Modificar la variable de entorno con el URI a la base de datos

Una vez levantado el mongo-db, inicializamos NestJs
```
npm run start:dev
```

