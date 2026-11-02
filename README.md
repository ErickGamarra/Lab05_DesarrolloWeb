# Laboratorio 05 - Validación y manejo de errores

Desarrollo de Aplicaciones Web - Tecsup

API de productos con Spring Boot, validación con DTO y manejo de errores.
La actividad agrega el campo `categoria` y la búsqueda por nombre.

## Cómo ejecutarlo

1. Crear la base de datos: `CREATE DATABASE laboratorio_api;`
2. Abrir la carpeta `demo01` en IntelliJ.
3. Ejecutar `Demo01Application` (puerto 8080).

## Rutas

- `GET /api/productos`
- `GET /api/productos/{id}`
- `GET /api/productos/buscar?nombre=monitor`
- `POST /api/productos`
- `PUT /api/productos/{id}`
- `DELETE /api/productos/{id}`
