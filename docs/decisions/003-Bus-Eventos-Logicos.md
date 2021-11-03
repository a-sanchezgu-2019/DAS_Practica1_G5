# Bus de Eventos Lógicos

* **Status**: accepted
* **Deciders**: Adrián Sánchez Guirado, Jorge Esteban Pérez, Miguel Ruiz Morán, Francis Cardi Pérez
* **Date**: 2021-10-27

Technical Story: Microservicio de mensajería

## Context and Problem Statement

Necesitamos que nuestras bases de datos se comuniquen a través de un bus de eventos lógicos

## Considered Options

* Tecnología de mensajería
* Bus dedicado

## Decision Outcome

Chosen option: "Bus dedicado", porque hace la comunicación más flexible

## Pros and Cons of the Options

### Tecnología de mensajería

Sistema de mensajería como RabbitMQ

* Buena, porque podemos determinar exactamente el destinatario de los datos
* Mala, porque requiere el mantenimiento de una infraestructura dedicada

### Bus dedicado

Bus de mensajería web como Azure Service Bus

* Buena, porque flexibilidad en las comunicaciones
* Mala, porque no podemos restringir el acceso a los datos desde módulos que no deberían
