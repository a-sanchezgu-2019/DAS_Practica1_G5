# Middleware Mensajeria

* **Status**: accepted
* **Deciders**: Adrián Sánchez Guirado, Jorge Esteban Pérez, Francis Cardi Pérez, Miguel Ruiz Morán
* **Date**: 2021-11-03

Technical Story: Middleware utilizado por la mensajería móvil.

## Context and Problem Statement

Queremos saber qué middleware utilizar para el servicio de mensajería a dispositivos móviles de los clientes

## Considered Options

* RabbitMQ
* ActiveMQ

## Decision Outcome

Chosen option: "RabbitMQ" porque tiene un mejor rendimiento

### Positive Consequences

* Mejor rendimiento que ActiveMQ

### Negative Consequences

* No tiene opción de recuperación de seguridad

## Pros and Cons of the Options

### RabbitMQ

* Bueno, porque tiene un mejor rendimiento
* Malo, porque no tiene opción de recuperación de seguridad

### ActiveMQ

* Bueno, porque tiene opción de recuperación de seguridad
* Malo, porque tiene un peor rendimiento
