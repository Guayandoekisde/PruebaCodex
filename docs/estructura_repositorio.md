# Estructura del Repositorio

Este documento define cómo organizar el proyecto para mantener orden, claridad y facilidad de evaluación.

## Árbol de directorios recomendado
```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

## Explicación de cada carpeta
- `docs/`: documentación principal de planeación, caso de uso y pruebas.
- `src/`: código fuente del prototipo mínimo.
- `scripts/`: scripts utilitarios para ejecutar el proyecto localmente.
- `tests/`: checklist y evidencia mínima de pruebas.

## Explicación de cada archivo
- `README.md`: guía general de la actividad, reglas y entregables.
- `docs/propuesta.md`: definición formal del proyecto.
- `docs/caso_de_uso.md`: descripción del flujo de uso principal.
- `docs/estructura_repositorio.md`: normas de organización del repo.
- `docs/plan_de_pruebas.md`: plan de pruebas detallado.
- `src/main.<ext>`: punto de entrada del prototipo (Python/C/Bash/ASM).
- `scripts/run.sh`: ejecución base adaptable por lenguaje.
- `tests/test_plan.md`: checklist corto de verificación.

## Reglas para nombrar archivos
- Usa minúsculas y guiones bajos.
- Evita espacios y caracteres especiales.
- Nombres claros y relacionados con su función.
- Mantén extensiones correctas (`.py`, `.c`, `.s`, `.sh`, `.md`).

## Reglas para evitar desorden
- No dupliques documentación entre archivos.
- Un archivo = una responsabilidad principal.
- Elimina scripts o notas temporales antes de entregar.
- Mantén funciones pequeñas y comentarios útiles.

## Nota final
Para esta actividad, prioriza pocos archivos, estructura limpia y funciones pequeñas. La meta es calidad de diseño, no cantidad de código.
