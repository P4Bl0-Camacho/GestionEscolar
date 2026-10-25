# Sistema de Gestión Escolar

Aplicación web desarrollada con ASP.NET Core MVC, Entity Framework Core y SQL Server.

## Integrante y entidades

| Integrante | Entidad |
|------------|---------|
| Pablo Camacho | Estudiante |
| Pablo Camacho | Maestro |
| Pablo Camacho | Aula |
| Pablo Camacho | Libro |

## Pasos para ejecutar el proyecto

1. Clonar el repositorio y abrir `GestionEscolar.sln` en Visual Studio 2026.
2. Verificar la cadena de conexión en `appsettings.json`:

   "DefaultConnection": "Server=localhost\\SQLEXPRESS;Database=GestionEscolarDB;Trusted_Connection=True;TrustServerCertificate=True;"

3. Abrir la Consola del Administrador de paquetes y ejecutar:

   Update-Database

4. Ejecutar el proyecto con F5.