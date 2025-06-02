<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Products Microservice

## Dev

1. Clonar el repositorio
2. Instalar las dependencias
3. Crear un archivo `.env` basado en el archivo `.env.example`
4. Ejecutar las migraciones de prisma `npx prisma migrate dev`
5. Levantar el servidor de Nats

```bash
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```

6. Ejecutar el proyecto `yarn start:dev`
