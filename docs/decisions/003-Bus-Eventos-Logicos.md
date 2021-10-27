# [Bus de Eventos Lógicos]

* Status: [proposed]
* Deciders: [Adrián Sánchez Guirado, Jorge Esteban Pérez, Miguel Ruiz Morán, Francis Cardi Pérez]
* Date: [2021-10-27]

Technical Story: [Microservicio de mensajería]

## Context and Problem Statement

[Necesitamos que nuestras bases de datos se comuniquen a través de un bus de eventos lógicos]

## Considered Options

* [Tecnología de mensajería]
* [Bus dedicado]

## Decision Outcome

Chosen option: "[Bus dedicado]", because [hace la comunicación más flexible]

## Pros and Cons of the Options

### [Tecnología de mensajería]

[Sistema de mensajería como RabbitMQ]

* Good, because [Podemos determinar exactamente el destinatario de los datos]
* Bad, because [Requiere el mantenimiento de una infraestructura dedicada]

### [Bus dedicado]

[Bus de mensajería web como Azure Service Bus]

* Good, because [Flexibilidad en las comunicaciones]
* Bad, because [No podemos restringir el acceso a los datos desde módulos que no deberían]
