# API REST

* **Status**: accepted
* **Deciders**: Adrián Sánchez Guirado, Jorge Esteban Pérez, Miguel Ruiz Morán, Francis Cardi Pérez
* **Date**: 2021-11-10

Technical Story: Protocolo para los Microservicios

## Context and Problem Statement

Queremos decidir qué protocolo utilizarán los microservicios de nuestro sistema.

## Considered Options

* API REST

## Decision Outcome

Chosen option: "API REST", porque nos permite unificar los módulos que utilizan HTTP.

### Positive Consequences

* Nos permite unificar los módulos que utilizan HTTP.
* Separa Cliente y Servidor, por lo que facilita el desarrollo para sistemas portables
* Independiente de la plataforma en la que se implemente

### Negative Consequences

* No tiene un estándar para tratar los datos.
* Tenemos que crear una infraestructura propia para mantener el estado.