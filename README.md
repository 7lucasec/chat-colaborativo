# Chat Colaborativo en Tiempo Real con WebSocket

## Descripción del proyecto

Este proyecto consiste en el desarrollo de un sistema de chat colaborativo en tiempo real mediante el uso de WebSocket, permitiendo la comunicación simultánea entre múltiples usuarios desde una aplicación web.

El sistema permite enviar y recibir mensajes instantáneamente, visualizar el historial de conversación y notificar cuando un usuario entra o sale del chat.

Además, se implementó autenticación mediante Google OAuth y acceso como invitado con asignación automática de nombre temporal.

## Objetivo

Desarrollar una funcionalidad básica de chat colaborativo en tiempo real entre múltiples usuarios, aplicando el uso de WebSocket para la comunicación bidireccional entre cliente y servidor.

## Funcionalidades principales

- Comunicación en tiempo real mediante WebSocket.
- Envío y recepción de mensajes entre múltiples usuarios.
- Interfaz web para el cliente.
- Historial visible de mensajes intercambiados.
- Asignación de nombre temporal para usuarios invitados.
- Notificación cuando un usuario entra o sale del chat.
- Autenticación mediante Google OAuth.
- Acceso como invitado.
- Almacenamiento de mensajes en base de datos SQLite.
- Deploy del proyecto en Railway.

## Tecnologías utilizadas

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js
- WebSocket (ws)
- Passport.js
- Google OAuth 2.0

### Base de datos
- SQLite

### Herramientas y despliegue
- GitHub
- Railway

## Estructura del proyecto

```bash
chat-colaborativo/
│
├── client/                     # Archivos del frontend
│   ├── index.html              # Estructura principal de la interfaz
│   ├── script.js               # Lógica del cliente y WebSocket
│   └── styles.css              # Estilos de la aplicación
│
├── server/                     # Backend del sistema
│   ├── auth.js                 # Configuración de autenticación
│   ├── server.js               # Servidor principal y WebSocket
│   │
│   └── database/               # Manejo de base de datos
│
├── .gitattributes
├── .gitignore
├── README.md                   # Documentación del proyecto
├── package.json                # Dependencias y scripts
├── package-lock.json
└── railway.json                # Configuración de Railway
```
## Instalación y acceso al proyecto

El sistema fue desarrollado utilizando Node.js, Express y WebSocket para permitir la comunicación en tiempo real entre múltiples usuarios conectados.

Debido a la implementación de autenticación mediante Google OAuth y el uso de variables de entorno, la ejecución correcta del proyecto requiere una configuración previa del entorno local.

Por esta razón, el proyecto se encuentra desplegado en Railway, permitiendo acceder y probar todas sus funcionalidades directamente desde el navegador sin necesidad de realizar configuraciones adicionales.

Enlace del proyecto desplegado:

```bash
https://chat-colaborativo-production-d40f.up.railway.app/
```

## Integrantes

### Grupo 26

- Apaza Arroyo Micaela Ruth
- Choque Flores Fidel
- Cusi Lucas Estrella Celeste
- Fuentes Soto Roger Adrian
- Pérez Sánchez Carlos Enrique
- Sandagorda Salvatierra Emerson Deyvis
- Yucra Tovar Andrea Rebeca
