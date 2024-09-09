# AppComunityHelp-Mobile

## Descripción del Proyecto

**AppComunityHelp-Mobile** es la aplicación móvil desarrollada en **Ionic** que complementa la plataforma de **AppComunityHelp**, un sistema orientado a mejorar la interacción y la colaboración comunitaria, facilitando la asistencia en situaciones de emergencia a través de alertas geolocalizadas y la creación de comunidades.

Este proyecto permite a los usuarios:
- Crear y gestionar **alertas SOS** con geolocalización.
- Unirse y participar en **comunidades** basadas en intereses o ubicación.
- Comunicarse y coordinarse dentro de las comunidades para ofrecer asistencia y colaboración.

La aplicación móvil interactúa con la **API REST** proporcionada por el proyecto **AppComunityHelp-API**, que centraliza la lógica de negocio y los datos.

## Tecnologías Utilizadas

- **Ionic Framework** (v5+)
- **Angular** (Frontend)
- **Capacitor** (para funcionalidades nativas)
- **Geolocalización**: Utiliza la geolocalización del dispositivo para rastrear la ubicación en las alertas SOS.
- **HttpClient**: Para consumir la API REST **AppComunityHelp-API**.

## Funcionalidades

### 1. Alertas SOS con Geolocalización
- Los usuarios pueden crear alertas de emergencia **SOS** con su ubicación actual.
- Las alertas son enviadas a los usuarios dentro de un radio determinado, permitiendo que reciban notificaciones y ofrezcan asistencia.

### 2. Gestión de Comunidades
- **Crear comunidades** según intereses o áreas geográficas.
- Unirse a comunidades según tres modos:
  - **Acceso directo**: Los usuarios pueden unirse sin restricciones.
  - **Aprobación del administrador**: El administrador debe aprobar las solicitudes de unión.
  - **Grupos cerrados**: Solo se puede acceder mediante invitación.
- Participación en comunidades a través de mensajes y eventos.

### 3. Geolocalización en Tiempo Real
- La aplicación obtiene la ubicación en tiempo real del usuario para generar alertas precisas.
- Los usuarios pueden visualizar las alertas dentro de un mapa interactivo.
