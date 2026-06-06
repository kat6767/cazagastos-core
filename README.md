# CazaGastos Core

Aplicación orientada a la gestión de gastos personales y grupales, diseñada para facilitar el registro de transacciones, el control financiero y la división de gastos entre múltiples usuarios.

## Descripción

CazaGastos es una propuesta de aplicación móvil enfocada en mejorar la administración de gastos cotidianos mediante una interfaz simple y accesible. El sistema busca permitir el registro rápido de gastos, el almacenamiento temporal sin conexión a internet y la gestión de gastos compartidos.

## Objetivos

* Registrar gastos de forma rápida y sencilla.
* Permitir el uso de la aplicación en modo offline.
* Facilitar la división de gastos grupales.
* Mejorar la experiencia de usuario mediante criterios UX/UI.
* Aplicar prácticas de aseguramiento de calidad de software (SQA).

## Funcionalidades principales

* Registro de gastos individuales.
* División de gastos entre múltiples participantes.
* Almacenamiento de datos sin conexión.
* Sincronización de información al recuperar internet.
* Carga de fotografías de tickets o facturas.
* Validación de datos de entrada.

## Estructura del proyecto

```text
├── .github/               # Flujos de trabajo automatizados (CI/CD)
├── src/                   # Código fuente de la aplicación móvil/web
├── tests/                 # Suite de pruebas unitarias e integración
├── docs/                  # Documentación técnica, requisitos e ISO 25010
├── .gitignore             # Archivos excluidos del control de versiones
└── README.md              # Descripción del proyecto y guía de configuración
```

## Estrategia de ramas

El proyecto utiliza una estrategia basada en GitFlow:

* main: versión estable.
* develop: integración de funcionalidades.
* feature/*: desarrollo de nuevas características.
* hotfix/*: correcciones urgentes.

## Métricas de calidad

* Registro del primer gasto en 15 segundos o menos.
* Tiempo de procesamiento de tickets menor o igual a 3 segundos.
* Complejidad ciclomática máxima de 10 por función.
* Conservación de datos en modo offline.

## Herramientas propuestas

* Git y GitHub
* GitHub Actions
* ESLint / SonarLint
* Figma
* Herramientas de pruebas unitarias e integración

## Equipo

Proyecto académico desarrollado para la asignatura Introducción a Ingeniería de Software.

## Estado del proyecto

Propuesta académica desarrollada con fines educativos.
