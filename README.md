# Chat Colaborativo en Tiempo Real con WebSocket

## Descripción del proyecto

Este proyecto consiste en el desarrollo de un sistema de chat colaborativo en tiempo real, orientado a permitir la comunicación simultánea entre varios usuarios conectados desde una aplicación web.

El sistema utiliza el protocolo **WebSocket** como medio principal de comunicación, permitiendo una conexión bidireccional y persistente entre el cliente y el servidor. Esto permite que los mensajes enviados por un usuario sean recibidos instantáneamente por los demás usuarios conectados, sin necesidad de recargar la página ni utilizar técnicas como polling o long-polling.

La aplicación cuenta con una interfaz web donde los usuarios pueden ingresar al chat, enviar mensajes, visualizar el historial de conversación y recibir notificaciones cuando otros usuarios se conectan o desconectan.

Además, el sistema implementa autenticación mediante **Google OAuth** y acceso como invitado. En caso de ingresar como invitado, se puede asignar un nombre temporal al usuario.

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
