# Lenguage Programación Microservicios

* **Status**: accepted
* **Deciders**: Adrián Sánchez Guirado, Jorge Esteban Pérez, Miguel Ruiz Morán, Francis Cardi Pérez
* **Date**: 2021-11-11

Technical Story: Lenguajes de Programación Microservicios

## Context and Problem Statement

Necesitamos decidir qué lenguaje de programación se utilizará para los microservicios

## Considered Options

* Python
* Java
* Golang
* Node.js

## Decision Outcome

Chosen option: "Python", porque es compatible con otros lenguajes de desarrollo web.

### Positive Consequences

* Gran compatibilidad con otros lenguajes de desarrollo web.
* Facilidad para los prototipos
* Se suele usar junto a la API RESTful

## Pros and Cons of the Options

### Python

* Buena, porque tiene una gran compatibilidad con otros lenguajes de desarrollo web.
* Buena, porque aporta facilidad para los prototipos
* Buena, porque tiene buena comunicación con la API RESTful

### Java

* Buena, porque proporciona una interfaz, conectividad con servicios de backend
* Mala, porque no tiene compatibilidad con otros lenguajes 

### Golang

* Buena, porque tiene buena comunicación con APIs, como RESTful
* Buena, porque aporta una capacidad profunda de testing
* Malo, porque necesita Frameworks muy específicos

### Node.js

* Buena, porque tiene poco coste
* Buena, porque tiene un gran rendimiento
* Mala, porque dificulta el mantenimiento de las aplicaciones

## Links

* [ADR-007](007-Microservicios-Logica-Negocio.md) - Microservicios Lógica Negocio
* [ADR-010](010-API-REST.md) - API REST
