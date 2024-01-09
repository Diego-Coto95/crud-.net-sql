# Sistema de Gestión Básica de CRUD en .Net - SQL

## Descripción
Este proyecto es un Sistema de Gestión que utiliza Windows Forms para la interfaz de usuario y SQL Server para la gestión de la base de datos. 
Permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar).

## Estado del Proyecto
El proyecto está finalizado y es una base para entender como se realiza un CRUD en Windows Forms con SQL.

## Capturas de Pantalla
<img width="313" alt="image" src="https://github.com/Diego-Coto95/crud-.net-sql/assets/44104619/2871f1d4-6751-4514-b122-532e131b342e">

## Instrucciones de Configuración
1. Clona el repositorio.
2. Configura la base de datos SQL Server según las instrucciones.
3. Ejecuta este comando para la creación de la base de datos en SQL.
  CREATE DATABASE MyTestDB
  USE MyTestDB
  CREATE TABLE UserTab
  (
    [ID] INT NOT NULL PRIMARY KEY, 
      [Name] NVARCHAR(50) NULL, 
      [Age] INT NULL
  )

4. Abre el proyecto en Visual Studio.
5. Ejecuta la aplicación.

## Requisitos del Sistema
- .NET Framework
- SQL Server
