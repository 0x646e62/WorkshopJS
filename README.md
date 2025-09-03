# Mesa de ayuda

## Stack Tecnológico

| Paquete                          | Propósito                                                                 |
| -------------------------------- | ------------------------------------------------------------------------- |
| express                          | FramekWork web minimalista para crear APIs REST                           |
| zod                              | Validación de datos con tipado fuerte, ideal para los esquemas en TS      |
| pino                             | Logger rápido y eficiente para producción                                 |
| pino-pretty                      | Formatea los logs de pino para desarrollo                                 |
| Json Web Token                   | Generación y verificación de tokens JWT para autenticación                |
| bcryptjs                         | Encriptación de contraseñas con hashing seguro                            |
| class-validator                  | Validación declarativa usando decoradores                                 |
| class-transform                  | Transformación de objetos entre clases y planes (DTOS)                    |
| reflect-metada                   | soporte para metadatos en decoradores (requerido por class-validator)     |
| cors                             | Middleware para habilitar CORS (Cross Origin Resource Sharing) en express |
| dotenv                           | cargar variables de entorno desde el archivo .env                         |
| morgan                           | Middleware para login de peticiones HTTP                                  |
| @prisma/client                   | Cliente en prisma para interactuar con la base de datos                   |
| tsx                              | ejecuta archivos typescript con soporte para ESM y hot-reload             |
| ts-node                          | Ejecutar archivos .ts directamente sin transpilar                         |
| nodemon                          | reinicar automaticamente el servidor al detectar cambios                  |
| prisma                           | ORM para modelar y migrar las bases de datos                              |
| vitest                           | Framework de testing rápido y compatible con Vite                         |
| supertest                        | Permite testear endpoints http de express                                 |
| eslint                           | Analizar el código para detectar errores y malas prácticas de código      |
| @typescript-eslint/parser        | Permite que Eslint entienda TypeScript                                    |
| @typescript-eslint/eslint-plugin | Reglas especificas de typescript                                          |
| eslint-confing-prettier          | Desactivar reglas que interfieren con Prettier                            |
| prettier                         | Formateador de código consistente                                         |
| husky                            | Ejecuta scripts en hooks de Git (ej. antes de hace commint)               |
| lint-staged                      | Aplica linters solo a archivos modificados en el commint                  |
| @types/...                       | Proveen tipado Ts a paquetes instalados                                   |

## Commando de arranque

1. Inicializamos el proyecto de NodeJS:

```bash
    npm init -y
```

2. Instalar TypeScript e iniciar la configuración:

```bash
    npm i -d typescript

    npx tsc --init
```

```bash
npm i express zod pino pino-pretty jsonwebtoken bcryptjs class-validator class-transform reflect-metadata cors dotenv morgan @prisma/client
npm i -D tsx ts-node nodemon
npm i -D @types/node @types/express @types/jsonwebtoken @types/cors @types/morgan
npm i -D prisma vitest supertest @types/supertest
npm i -D eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-confing-prettier
npm i -D husky prettier lint-staged
```
