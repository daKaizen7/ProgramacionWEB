# ProgramacionWEB

Este proyecto es una aplicación web universitaria que integra:

- 🔧 Backend en **ASP.NET Core Web API**
- 💻 Frontend en **Blazor Server**
- 🗄 Base de datos SQL Server

## 📁 Estructura del repositorio

ProgramacionWEB/
├── FrontBlazor/ # Frontend en Blazor Server
├── csharpapigenerica/ # Backend en ASP.NET Core

yaml
Copiar
Editar

---

## 🚀 Cómo ejecutar el proyecto

### 🔹 Requisitos

- Visual Studio 2022 o superior
- .NET SDK 6.0 o superior
- SQL Server
- (Opcional) Postman o Swagger para probar la API

---

### 🔹 Backend (ASP.NET Core API)

1. Abre `csharpapigenerica.sln` en Visual Studio.
2. Asegúrate de configurar correctamente la cadena de conexión a SQL Server en `appsettings.json`.
3. Ejecuta el proyecto para exponer la API en Swagger (`https://localhost:xxxx/swagger`).

---

### 🔹 Frontend (Blazor Server)

1. Abre el proyecto `FrontBlazor` desde Visual Studio.
2. Asegúrate de que las llamadas a la API en tu código Blazor usen la misma URL donde corre el backend.
3. Ejecuta el proyecto y navega por la interfaz Blazor.

---

## ✅ Funcionalidades previstas

- [ ] Listado de entidades desde la base de datos
- [ ] Creación, edición y eliminación
- [ ] Interfaz de usuario en Blazor
- [ ] Validaciones y estilos

---

## 🤝 Créditos

Este proyecto fue desarrollado como parte de la asignatura de Aplicaciones y Servicios Web.

---

## 🛠 Tecnologías utilizadas

- C#
- ASP.NET Core
- Entity Framework Core
- Blazor Server
- SQL Server
