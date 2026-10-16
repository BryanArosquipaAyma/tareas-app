# Guía 8 - Aplicación Full Stack React + Node.js

## Descripción

Aplicación web de gestión de tareas desarrollada
con React, Vite, Node.js y Express.

Permite crear, consultar, completar y eliminar tareas
mediante una API REST.

## Tecnologías

- React
- Vite
- Node.js
- Express
- Git y GitHub
- Render
- Vercel

## Enlaces del proyecto

### Código fuente
https://github.com/BryanArosquipaAyma/tareas-app

### Frontend publicado
https://tareas-app-sigma-one.vercel.app

### Backend publicado
https://tareas-app-xeig.onrender.com/api/tareas

## Funcionalidades

1. Mostrar tareas existentes.
2. Agregar nuevas tareas.
3. Marcar tareas como completadas.
4. Eliminar tareas.
5. Consumir una API REST desde React.

## Instalación local

### Backend

cd server
npm install
npm run dev

Servidor:
http://localhost:3001

### Frontend

En otra terminal:

cd client
npm install
npm run dev

Aplicación:
http://localhost:5173

## Arquitectura

Frontend: React + Vite

Backend: Node.js + Express

Comunicación: API REST mediante HTTP.

## Almacenamiento

Las tareas se almacenan temporalmente en memoria
del servidor. Los datos pueden reiniciarse cuando
el servicio vuelve a ejecutarse.

## Despliegue

El código fuente está alojado en GitHub.

El backend se encuentra desplegado en Render.

El frontend está publicado en Vercel.

La conexión entre ambas aplicaciones utiliza
variables de entorno y configuración CORS.

## Pruebas realizadas

- Consulta de tareas.
- Creación de tareas.
- Actualización del estado de tareas.
- Eliminación de tareas.
- Verificación del funcionamiento en producción.

## Conclusión

Se desarrolló y publicó una aplicación web Full Stack
que integra React con Node.js mediante una API REST.

Se comprobó el funcionamiento de las operaciones CRUD
y el despliegue de los componentes frontend y backend
en servicios independientes.
