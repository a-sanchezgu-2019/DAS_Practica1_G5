# Gestión Controladores BBDD

* **Status**: accepted
* **Deciders**: Adrián Sánchez Guirado, Jorge Esteban Pérez, Miguel Ruiz Morán, Francis Cardi Pérez
* **Date**: 2021-11-11

Technical Story: Gestión de los controladores de las Bases de Datos de nuestro sistema

## Context and Problem Statement

Nuestro sistema cuenta con varios controladores de distintas bases de datos y un bus de eventos lógicos

## Considered Options

* Utilizar el patrón Facade
* Agruparlas en su propio paquete

## Decision Outcome

Chosen option: "Utilizar el patrón Facade", porque unifica el acceso a los datos

### Positive Consequences

* Unificamos todos los controladores a uno
* Facilita las consultas

### Negative Consequences

* Si la conexión con este módulo falla, no se tendrá acceso a ninguna base de datos.

## Pros and Cons of the Options

### Utilizar el patrón Facade

* Bueno, porque unifica todos los controladores en uno
* Bueno, porque facilita las consultas
* Malo, porque si el módulo falla, se perderá el acceso a todas las bases de datos
* Malo, porque un cambio de base de datos requiere modificar el módulo

### Agruparlas en su propio paquete

* Buena, porque es menos sensible al fallo
* Malo, porque dificulta la monitorización de los datos

## Links

* [ADR-002](002-Controlador-MongoDB.md) - Controlador MongoDB
* [ADR-003](003-Bus-Eventos-Logicos.md) - Bus de Eventos Lógicos
