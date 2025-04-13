
# Proyecto Curso Backend Node.js

Este proyecto es una API RESTful construida con **Node.js** y **Express**. Está orientada a la gestión de productos, categorías y usuarios para una tienda en línea. La API permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre los productos, y también incluye middleware para el manejo de errores y validación de datos.

El proyecto utiliza **Joi** para validar los datos de los productos, y **Boom** para el manejo de errores HTTP personalizados. Se incluye un servicio que simula la creación de productos falsos utilizando **Faker**.

## Características principales:
- **Rutas** para manejar operaciones CRUD sobre productos, categorías y usuarios.
- **Validación** de entradas utilizando **Joi**.
- **Manejo de errores** con **Boom**.
- **Middleware** para la gestión de errores.
- **Dependencias**: `express`, `faker`, `joi`, `boom`, entre otras.

## Instrucciones para clonar el proyecto:

Para clonar este proyecto en tu máquina, puedes usar el siguiente comando:

```bash
git clone https://github.com/Perezcortes/curso-backend-nodejs.git
```

## Pasos para correr el proyecto:

1. Clona el repositorio a tu máquina local:

   ```bash
   git clone https://github.com/Perezcortes/curso-backend-nodejs.git
   cd curso-backend-nodejs
   ```

2. Instala las dependencias del proyecto:

   ```bash
   npm install
   ```

3. Corre el proyecto en modo desarrollo:

   ```bash
   npm run dev
   ```

   O si prefieres ejecutar el proyecto en producción:

   ```bash
   npm start
   ```

4. Accede a la API en `http://localhost:3000/` y prueba las rutas definidas.

## Estructura de directorios:

```
perezcortes-curso-backend-nodejs/
├── index.js
├── package.json
├── .editorconfig
├── .eslintrc.json
├── middlewares/
│   ├── error.handler.js
│   └── validator.handler.js
├── routes/
│   ├── categories.router.js
│   ├── index.js
│   ├── products.router.js
│   └── users.router.js
├── schemas/
│   └── product.schema.js
└── services/
    └── product.service.js
```

## Tecnologías usadas:
- **Node.js**: Entorno de ejecución de JavaScript del lado del servidor.
- **Express**: Framework web para Node.js.
- **Joi**: Librería para validaciones de datos.
- **Boom**: Librería para manejo de errores HTTP.
- **Faker**: Generador de datos falsos para simular productos.

## Archivos clave:
- **index.js**: Configuración principal del servidor y rutas.
- **middlewares/error.handler.js**: Manejo de errores globales.
- **middlewares/validator.handler.js**: Middleware para validar los datos de las peticiones.
- **routes/products.router.js**: Rutas para manejar productos (GET, POST, PUT, DELETE).
- **services/product.service.js**: Lógica para manejar los productos, incluyendo simulación de creación de productos falsos.

## Datos del autor:
- **Correo**: 9531447499a@gmail.com
- **Usuario de GitHub**: [Perezcortes](https://github.com/Perezcortes)
