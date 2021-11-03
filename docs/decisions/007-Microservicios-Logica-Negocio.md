# Microservicios Lógica Negocio

* **Status**: accepted
* **Deciders**: Adrián Sánchez Guirado, Jorge Esteban Pérez, Francis Cardi Pérez, Miguel Ruiz Morán
* **Date**: 2021-11-03

Technical Story: Microservicios de la Lógica de Negocio

## Context and Problem Statement

Queremos saber cuántos y qué microservicios utilizaremos para manejar la lógica del negocio.

## Considered Options

* Compra, Devolucion, Inventario, Identificacion, Pago y Buscador
* Compra, Devolucion, Inventario, Identificacion, Pago, Buscador y Prefencias

## Decision Outcome

Chosen option: Compra, Devolucion, Inventario, Identificacion, Pago, Buscador y Prefencias porque aumentamos la modularidad de los componentes

### Positive Consequences

Aumenta la modularidad de los servicios y se cubren todas las funcionalidades necesarias

## Pros and Cons of the Options

### Compra, Devolucion, Inventario, Identificacion, Pago y Buscador

* Buena, porque es más compacto, ya que las Preferencias estarían recogidas en el Buscador
* Mala, porque no permite acceder directamente a las preferencias de los usuarios

### Compra, Devolucion, Inventario, Identificacion, Pago, Buscador y Preferencias

* Buena, porque permite acceder directamente a las preferencias de los usuarios
* Mala, porque es un microservicio más que sincronizar
