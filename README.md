# Backend en Nest
```
docker compose up -d
```
Copiar el ```.env.template``` y renombrarlo a ```.env```

## Comandos usados
```
docker compose up -d //Para lanzar el docker
nest g resource auth //Para generar un modulo de nestJs
npm i @nestjs/mongoose mongoose //Para que se pueda conectar a mongoDB
npm i @nestjs/config //Para obtener datos de mi archivo de configuracion .env
npm i class-validator class-transformer //Para obligar que los request sean como las definiciones de los DTO
npm i bcryptjs //Para encriptar
npm i --save-dev @types/bcryptjs //Para obtener los archivos de definicion (tipos de datos) de bcryptjs, ya que esta escrito en JS
npm install --save @nestjs/jwt //JWT token
nest g gu auth/guards/auth //Creacion de guard

```