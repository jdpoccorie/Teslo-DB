<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# TesloDB

1. Clonar el proyecto
2. `npm install`
3. Clonar el archivo __.env.template__ y renombrarlo a __.env__
4. Cambiar las variables de entorno
5. Levantar la base de datos
   ```
   docker-compose up -d
   ```
6. Ejecutar SEED para rellenar con datos la base de datos:
   ```
   (POST)
   http://localhost:3000/api/seed
   ```
7. Levantar: `npm run start:dev`