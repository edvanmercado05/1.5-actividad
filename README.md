# 1.5-actividad

# Ejemplo de Node.js con Firebase

Aplicación web CRUD utilizando Firebase Admin SDK con Firestore, Node.js y Express.

## Características
- Uso del SDK de Firebase Admin para operaciones con la base de datos.
- Integración con Firestore para funcionalidades CRUD.
- Framework Express para enrutamiento.
- Plantillas Handlebars para las vistas.
- Morgan para registro de solicitudes HTTP.
- Soporte para variables de entorno con dotenv.

## Requisitos previos
- Node.js (v14 o superior).
- npm (v6 o superior).
- Un proyecto de Firebase con Firestore habilitado.
- Archivo de clave de cuenta de servicio para el SDK de Firebase Admin.

## Variables de entorno
Crea un archivo `.env` en el directorio raíz y agrega lo siguiente:
GOOGLE_APPLICATION_CREDENTIALS=ruta/a/tu/serviceAccountKey.json


## Instalación
1. Clona este repositorio:
   ```bash
   git clone <url-del-repositorio>
   cd <carpeta-del-repositorio>
Instala las dependencias:

npm install
Uso
Desarrollo
Ejecuta la aplicación en modo desarrollo:


npm run dev
Producción
Inicia la aplicación en modo producción:


npm start
Estructura del proyecto

nodejs-firebase-example-master/
├── src/
│   ├── index.js        # Punto de entrada principal de la aplicación
│   ├── routes/         # Rutas de Express
│   ├── views/          # Plantillas Handlebars
│   ├── services/       # Lógica relacionada con Firebase
├── package.json        # Configuración del proyecto
├── .gitignore          # Archivos ignorados por Git
├── README.md           # Documentación
Recursos
Configuración de Firebase Admin SDK
Gestión de datos en Firestore
Patrones de fondo CSS
Temas de Bootstrap con Bootswatch






