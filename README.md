<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clona el repositorio
2. Ejecutar

```
npm i
```

3. Tener nest CLI instalado

```
npm i -g @nestjs/cli
```

4. Levantar la base de datos

```
docker-compose up -d
```

5. Clonar el archivo **.env.template** y renombrarlo la copia a **.env**

6. Llenar las variables de entorno definidas en el archivo **.env**.

7. Ejecutar el servidor

```
npm run start:dev
```

8. Reconstruir la base de datos con la semilla

```
http://localhost:3000/api/v2/seed
```

## Stack usado

- MongoDB
- Nest
