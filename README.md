<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar

```
yarn install
```

3. Tener Nest CLI instalado

```
nmp i -g @nestjs/cli
```

4. Levantar la BD

```
docker-compose up -d
```

5. Clonar el archivo __.env.example__ y renombrar la copia a __.env__

6. Llenar las variables de entorno definidas en __.env__

7. Ejecutar la app en desarrollo con

```
yarn start:dev
```

8. Reconstruir la BD con el Seed

```
http://localhost:3000/api/seed
```

## Stack usado

- MongoDB
- Nest
