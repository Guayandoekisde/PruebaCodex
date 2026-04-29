# Actividad: Diseño de Práctica Temática Pequeña para GitHub Classroom

## Descripción general
En esta actividad vas a diseñar una propuesta de práctica temática pequeña enfocada en arquitectura de computadoras, programación de sistemas y trabajo en terminal. La meta principal es planear, justificar y documentar bien una idea viable antes de implementar código.

Esta plantilla está pensada para publicarse en GitHub Classroom sin plantilla previa, de modo que cada estudiante complete su propio proyecto desde cero con una estructura organizada.

## Objetivo de aprendizaje
Al finalizar esta actividad, el estudiante será capaz de:
- Definir un problema concreto y acotado.
- Justificar la elección de lenguaje para una solución de sistemas pequeña.
- Documentar caso de uso, alcance, limitaciones y plan de pruebas.
- Organizar un repositorio limpio y mantenible.
- Implementar, de forma opcional, un prototipo mínimo funcional.

## Lenguajes permitidos
- ARM64 Assembly
- C
- Python
- Bash

## Reglas para mantener el proyecto pequeño
- Enfócate en **una sola necesidad principal**.
- Limita el prototipo a funcionalidades esenciales (MVP).
- Evita interfaces gráficas, frameworks y librerías pesadas.
- No uses APIs externas, nube, Docker ni bases de datos.
- Usa archivos y scripts mínimos, con funciones cortas y claras.
- Si eliges ARM64 Assembly, selecciona un problema muy pequeño.

## Entregables esperados
1. Propuesta completa en `docs/propuesta.md`.
2. Caso de uso completo en `docs/caso_de_uso.md`.
3. Explicación de estructura en `docs/estructura_repositorio.md`.
4. Plan de pruebas en `docs/plan_de_pruebas.md` y checklist en `tests/test_plan.md`.
5. Estructura del repositorio conforme a lo solicitado.
6. Prototipo mínimo en `src/main.<ext>` (opcional pero recomendado).

## Instrucciones para el estudiante
1. Lee este `README.md` completo.
2. Elige un tema pequeño y uno de los lenguajes permitidos.
3. Llena primero la documentación en `docs/`.
4. Define pruebas mínimas realistas en `docs/plan_de_pruebas.md` y `tests/test_plan.md`.
5. Ajusta `scripts/run.sh` para tu lenguaje elegido.
6. Implementa un prototipo mínimo **solo después** de cerrar la propuesta.
7. Verifica que el repositorio esté limpio, ejecutable y fácil de revisar.

## Ejemplos de temas posibles
- “Mini Toolkit en ARM64”
- “Asistente de Estudio en Terminal”
- “Reporteador de Información del Sistema”
- “Organizador de Archivos”
- “Juego de Aprendizaje en Línea de Comandos”

## Criterios generales de evaluación
- Claridad del problema y del caso de uso.
- Coherencia entre objetivo, alcance y lenguaje elegido.
- Calidad de la documentación técnica.
- Orden y consistencia en la estructura del repositorio.
- Viabilidad técnica del proyecto en tiempo y complejidad.
- Calidad del plan de pruebas y criterios de éxito.
- (Opcional) funcionamiento básico del prototipo mínimo.

> **Nota importante:** En esta actividad se evalúa primero la documentación y planeación. La implementación de código es opcional y, si se hace, debe ser un prototipo pequeño y bien justificado.
