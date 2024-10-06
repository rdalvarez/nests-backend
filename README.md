# Backend en Nest

1. Comando para ejecutar el archivo docker-compose.yml 
```
docker compose up -d
```
``-d `` es para que se ejecute de manera desenlazada de la terminal.

2. Copiar el ``.env.template`` y renombrarlo a ``.env``. 

3. Modificar la variable de entorno con el URI a la base de datos

4. Una vez levantado el *mongo-db*, inicializamos NestJs
```
npm run start:dev
```

