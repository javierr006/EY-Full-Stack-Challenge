EY Full Stack Challenge

Este proyecto es un sistema de gestión de tareas desarrollado como parte del reto EY Full Stack Challenge.
Permite crear, consultar, actualizar y eliminar tareas utilizando una API REST construida en .NET Core (C#) y un frontend en React.

Tecnologías Utilizadas

Backend

C# / .NET 8 (ASP.NET Core Web API)

Entity Framework Core

SQLite como base de datos local

Swagger UI para documentación interactiva de la API

Frontend

React.js (Create React App)

Axios para peticiones HTTP

SweetAlert2 para notificaciones

React Icons para iconografía

CSS personalizado siguiendo lineamientos visuales de EY

Instalación y Ejecución

Clonar el repositorio

git clone https://github.com/javierr006/EY-Full-Stack-Challenge.git
cd EY-Full-Stack-Challenge


Backend (.NET Core)

cd backend/TaskManagerAPI
dotnet restore
dotnet run


El servidor iniciará normalmente en:

https://localhost:7000/api/tasks


Documentación Swagger:

https://localhost:7000/swagger


Frontend (React)
En otra terminal:

cd frontend
npm install
npm start


Interfaz disponible en:

http://localhost:3000


Funcionalidades

Crear tareas mediante un formulario con validaciones y notificación visual al guardar.

Consultar tareas con tabla dinámica que lista todos los registros.

Búsqueda por ID, nombre o estado.

Iconos de estado con descripción al pasar el cursor.

Editar tareas con búsqueda por ID, carga automática en el formulario y opciones para actualizar o eliminar.

Confirmaciones antes de realizar cambios o eliminar tareas.

Puntos Adicionales Implementados

Swagger para documentación automática de la API.

Validaciones básicas en el modelo TaskItem.

Notificaciones visuales utilizando SweetAlert2.

Diseño visual basado en la identidad gráfica de EY.

Autor

Javier Caná.
Desarrollador Full Stack — React y .NET Core
Guatemala

Estructura del Proyecto

EY-Full-Stack-Challenge/
│
├── backend/
│   └── TaskManagerAPI/
│       ├── Controllers/
│       ├── Models/
│       ├── Data/
│       └── Program.cs
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── assets/
│   │   └── App.js
│   ├── package.json
│   └── README.md
│
└── .gitignore
