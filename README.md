# Software Architecture Documentation Learning Repository

Ruta práctica para aprender a documentar arquitectura de software con **C4, ADR, UML, atributos de calidad y documentación como código**.

La meta no es acumular notaciones, sino poder responder cinco preguntas sobre un sistema:

1. ¿Qué es el sistema y con quién interactúa?
2. ¿Cómo está descompuesto?
3. ¿Cómo se comporta en escenarios importantes?
4. ¿Por qué se tomaron las decisiones arquitectónicas?
5. ¿Qué atributos de calidad debe satisfacer y cómo se verifican?

## Herramientas sugeridas

- **Structurizr DSL** para modelar C4 como un modelo reutilizable.
- **PlantUML** para UML y diagramas complementarios.
- **Markdown + Git** para ADR y documentación.
- CI opcional para renderizar y validar documentación.

## Estructura

```text
.
├── ROADMAP.md
├── resources/
│   ├── c4.md
│   ├── adr.md
│   ├── uml.md
│   ├── quality.md
│   └── docs-as-code.md
├── templates/
│   ├── adr-template.md
│   ├── quality-scenario-template.md
│   └── architecture-review-checklist.md
├── labs/
│   ├── 01-c4.md
│   ├── 02-adr.md
│   ├── 03-uml.md
│   ├── 04-quality.md
│   └── 05-living-architecture.md
└── capstone/
    └── README.md
```

## Resultado esperado

Al terminar deberías tener un dossier arquitectónico pequeño pero profesional, versionable en Git y mantenible junto con el código.
