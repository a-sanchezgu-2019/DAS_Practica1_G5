# Accesibilidad Dispositivos Portables

* **Status**: accepted
* **Deciders**: Adrián Sánchez Guirado, Jorge Esteban Pérez, Miguel Ruiz Morán, Francis Cardi Pérez
* **Date**: 2021-11-09

Technical Story: Accesibilidad de dispositivos portables

## Context and Problem Statement

Queremos decidir cómo aumentar la accesibilidad de dispositivos móviles, como smartphones o tablets

## Considered Options

* Applicación Web Progresiva (PWA)
* Aplicación dedicada para dispositivos portables

## Decision Outcome

Chosen option: "Applicación Web Progresiva (PWA)", porque no se necesitan funcionalidades extra para estos dispositivos

### Positive Consequences

* Menor tiempo de desarrollo
* Cualquier cambio al sistema se aplica directamente en todas las plataformas

### Negative Consequences

* Cualquier fallo en la página web se puede extender hasta la aplicación

## Pros and Cons of the Options

### Applicación Web Progresiva (PWA)

* Buena, porque cualquier cambio en el sistema no conlleva tener que cambiar otra versión
* Mala, porque cualquier error en la página web afectará a esta aplicación

### Aplicación nativa para dispositivos portables

* Buena, porque puede optimizarse más para estos dispositivos
* Mala, porque conlleva un mayor trabajo