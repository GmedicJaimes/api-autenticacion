
# API de Registro e Inicio de Sesión

## Descripción
Servicio web REST desarrollado con Node.js y Express
para registrar usuarios y validar sus credenciales.

## Tecnologías
- Node.js
- Express
- bcryptjs
- Git y GitHub

## Instalación
1. Instalar Node.js.
2. Abrir la carpeta del proyecto en la terminal.
3. Ejecutar npm install.
4. Ejecutar npm start.

## Rutas
- GET / : verifica el estado del servicio.
- POST /api/auth/register : registra un usuario.
- POST /api/auth/login : valida las credenciales.

## Pruebas
Enviar las solicitudes mediante Postman o Thunder Client,
usando el cuerpo JSON indicado en la documentación.

## Almacenamiento
Los usuarios de esta demostración se guardan en
data/users.json. Las contraseñas se almacenan como hash.
