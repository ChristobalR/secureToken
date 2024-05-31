SecureToken

Este repositorio contiene dos aplicaciones que trabajan en conjunto para proporcionar un sistema de autenticación y autorización seguro utilizando React y Node.js Express.
React App - LoginPage

Esta aplicación de React proporciona una interfaz de usuario para iniciar sesión. Utiliza Axios para realizar solicitudes a la API Express y React Router DOM para la navegación entre páginas protegidas y no protegidas.
Node.js Express API - API

Esta API Express proporciona endpoints para autenticación de usuarios, validación de tokens y creación de mensajes. Utiliza MongoDB como base de datos y JWT para la autenticación basada en tokens.
Dependencias Principales
En la Aplicación de React:

    Axios: Cliente HTTP basado en promesas para el navegador y Node.js.
    React Router DOM: Librería de enrutamiento para React que permite la navegación entre componentes.

En la API de Node.js Express:

    Express: Framework web para Node.js que facilita la creación de API RESTful.
    Mongoose: Librería de modelado de datos para MongoDB y Node.js.
    Body-parser: Middleware para Node.js que analiza los cuerpos de las solicitudes entrantes en un middleware antes de que se manejen las solicitudes.
    Cookie-parser: Middleware para Node.js que analiza las cookies de las solicitudes entrantes.
    Dotenv: Módulo de dependencia que carga variables de entorno desde un archivo .env.
    Morgan: Middleware de registro de solicitudes HTTP para Node.js.

Ejecución del Proyecto

    Clona este repositorio en tu máquina local.
    Instala las dependencias del cliente y del servidor ejecutando npm install en ambos directorios (api y loginpage).
    Inicia el servidor ejecutando npm start en el directorio api.
    Inicia la aplicación de React ejecutando npm start en el directorio loginpage.
    La aplicación estará disponible en tu navegador en la dirección http://localhost:3000