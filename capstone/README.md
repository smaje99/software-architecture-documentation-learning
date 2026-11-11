# Capstone — Documentación completa de una arquitectura

Usa un proyecto real; idealmente uno que esté en construcción para que las decisiones tengan consecuencias reales.

## Dossier mínimo

```text
architecture/
├── README.md
├── c4/
│   ├── context.*
│   ├── containers.*
│   ├── deployment.*
│   └── dynamic-*.*
├── uml/
│   └── sequence-*.puml
├── adr/
│   ├── 0001-*.md
│   ├── 0002-*.md
│   └── ...
├── quality/
│   └── scenarios.md
├── risks.md
└── glossary.md
```

## Reto recomendado

Documenta **BPMNPlay** como proyecto transversal:

1. Contexto y contenedores.
2. Un deployment de la primera versión.
3. Un escenario dinámico de una sesión/evaluación.
4. ADR de backend, frontend, motor BPM/procesos, persistencia y tiempo real.
5. Escenarios de calidad para concurrencia, trazabilidad, mantenibilidad y seguridad.
6. Revisión final con el checklist.

El objetivo final es que otra persona pueda comprender la arquitectura, sus razones y sus restricciones sin depender de una explicación oral.
