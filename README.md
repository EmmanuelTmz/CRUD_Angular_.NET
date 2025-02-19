# Proyecto CRUD con Angular 9 y .NET Core

Este proyecto es una aplicación web que implementa operaciones CRUD (Crear, Leer, Actualizar, Eliminar) utilizando Angular 9 para el frontend y .NET Core 3.1 para el backend. Se emplea Entity Framework Core 3.1 como ORM y MySQL como sistema de gestión de bases de datos.

## Descripción del Proyecto

El objetivo de este proyecto es demostrar cómo construir una aplicación completa desde cero, integrando las siguientes tecnologías:

- **Frontend**: Angular 9, HTML, CSS, JavaScript y Bootstrap 4.
- **Backend**: .NET Core 3.1.
- **ORM**: Entity Framework Core 3.1.
- **Base de Datos**: MySQL.

En el frontend, se desarrollan componentes reutilizables, servicios para la comunicación con el backend, formularios con validaciones y navegación entre vistas. En el backend, se crea una API RESTful con los métodos HTTP GET, POST, PUT y DELETE para gestionar las operaciones sobre los datos. Entity Framework Core se utiliza para mapear las entidades y realizar las operaciones en la base de datos MySQL.

## Características Principales

- **Operaciones CRUD**: Gestión completa de registros a través de la interfaz web.
- **API RESTful**: Implementación de una API con endpoints para cada operación CRUD.
- **Validación de Formularios**: Formularios dinámicos con validaciones en el frontend.
- **Comunicación HTTP**: Uso de servicios en Angular para interactuar con la API backend.
- **Diseño Responsivo**: Interfaz de usuario adaptada a diferentes dispositivos gracias a Bootstrap 4.

## Requisitos Previos

Para ejecutar este proyecto, es necesario tener instalados los siguientes componentes:

- **Node.js**: Para ejecutar Angular y sus dependencias.
- **Angular CLI**: Herramienta de línea de comandos para gestionar proyectos Angular.
- **Visual Studio 2019**: IDE para desarrollar y ejecutar el proyecto backend en .NET Core.
- **MySQL**: Sistema de gestión de bases de datos para almacenar la información.
- **Conocimientos Básicos**: Familiaridad con HTML, CSS, JavaScript, C#, .NET Core y Angular.

## Instrucciones de Instalación

1. **Clonar el Repositorio**: Descarga o clona este repositorio en tu máquina local.

2. **Configuración del Backend**:
   - Abre el proyecto backend en Visual Studio 2019.
   - Configura la cadena de conexión a la base de datos MySQL en el archivo `appsettings.json`.
   - Ejecuta las migraciones de Entity Framework para crear la base de datos y las tablas necesarias.
   - Inicia el proyecto backend para que la API esté disponible.

3. **Configuración del Frontend**:
   - Navega a la carpeta del proyecto frontend.
   - Ejecuta `npm install` para instalar las dependencias de Angular.
   - Configura la URL de la API backend en los servicios de Angular si es necesario.
   - Inicia la aplicación frontend con `ng serve` y accede a `http://localhost:4200` en tu navegador.

## Recursos Adicionales

Para obtener más información y recursos relacionados con este proyecto, puedes consultar los siguientes enlaces:

- [Curso en Udemy: CRUD Angular + .NET Core + Entity Framework Core + MySQL](https://www.udemy.com/course/crud-angular-9-net-core-entity-framework-core-mysql/)
- [Repositorio Backend en GitHub](https://github.com/mnbenavides/BETarjeta)
- [Repositorio Frontend en GitHub](https://github.com/andracin/Angular-Mysql-Crud-App)

Estos recursos ofrecen tutoriales detallados, ejemplos de código y documentación para ayudarte a comprender y ampliar las funcionalidades de este proyecto.
