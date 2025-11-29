# Backstage  con Plugin AI Assistant de Rodie 
### Proyecto Demostración de Implementación de un Internal Developement Platform - IDP 

### Stack: 
- [Backstage](https://backstage.io)
- [Rodie.io](https://roadie.io)
- [Dev Container](https://code.visualstudio.com/docs/devcontainers/containers)
- Docker Compose
- NodeJS v20
- PostgreSQL


### Desripción
Este proyecto tiene como proposito probar las capacidades del plugin Backstage AI Assistant RAG de  [Rodie](https://roadie.io) sobre [Backstage](https://backstage.io)  permitiendo obtener respuestas más detalladas de  entidades, TechDocs, especificaciones de OpenAPI y conocimientos técnicos mediante generación aumentada por recuperación (RAG). 

Con este plugin, los usuarios de Backstage pueden hacer preguntas En lenguaje natural y recibir respuestas basadas en la propia documentación y metadatos.

### Stack
Utilizaremos el proyecto de Backstae para el despliegue localmente usando devcontainer

Crear App
```
npx @backstage/create-app@latest
```

```sh
yarn install
yarn start
```
