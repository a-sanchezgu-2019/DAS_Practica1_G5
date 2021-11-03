# Middleware Microservicios

* **Status**: accepted
* **Deciders**: Adrián Sánchez Guirado, Jorge Esteban Pérez, Miguel Ruiz Morán, Francis Cardi Pérez
* **Date**: 2021-11-03

Technical Story: Middleware que alberga los microservicios

## Context and Problem Statement

Queremos decidir qué middleware utilizaremos para albergar los microservicios

## Considered Options

* Docker Swarm
* Kubernetes

## Decision Outcome

Chosen option: "Kubernetes", porque permite configurar el balanceo de carga y tiene una mayor personalización.

### Positive Consequences

* Nos permite organizar los microservicios mediante contenedores
* Permite una gran escalabilidad

## Pros and Cons of the Options

### Docker Swarm

* Bueno, porque permite organizar los microservicios mediante controladores
* Malo, porque no permite personalizar el balanceo de carga.

### Kubernetes

* Bueno, porque permite organizar los microservicios mediante controladores
* Bueno, porque permite personalizar el balanceo de carga
* Bueno, porque permite una gran escalabilidad
