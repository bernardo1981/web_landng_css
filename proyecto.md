landing-page/
│
├── index.html
├── styles/
│   └── main.css
├── scripts/
│   ├── main.js
│   └── config.example.js
├── .gitignore
├── README.md
└── package.json

# Contenido de .gitignore
node_modules/
.env
scripts/config.js

# Contenido de config.example.js
const config = {
  firebase: {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_AUTH_DOMAIN",
    projectId: "YOUR_PROJECT_ID",
    // ... otras configuraciones de Firebase
  }
};

# Contenido de README.md
# Landing Page LogisTech

Esta es la landing page para LogisTech, una empresa de soluciones logísticas.

## Configuración

1. Clona este repositorio
2. Copia `scripts/config.example.js` a `scripts/config.js` y llena con tus credenciales
3. Instala las dependencias con `npm install`
4. Ejecuta el proyecto con `npm start`

## Variables de Entorno

Este proyecto utiliza las siguientes variables de entorno:

- FIREBASE_API_KEY
- FIREBASE_AUTH_DOMAIN
- FIREBASE_PROJECT_ID

Asegúrate de configurar estas variables en tu entorno de desarrollo y producción.

# Contenido de package.json
{
  "name": "logistech-landing-page",
  "version": "1.0.0",
  "description": "Landing page for LogisTech",
  "main": "index.html",
  "scripts": {
    "start": "http-server"
  },
  "dependencies": {
    "firebase": "^8.6.8"
  },
  "devDependencies": {
    "http-server": "^0.12.3"
  }
}