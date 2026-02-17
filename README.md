# QA Testing Report: Urban.Lunch App - Sprint 6

Analista: Reynier Martin
Proyecto: Urban.Lunch (Android Application)
Herramientas: Android Studio, Jira, Excel.

## Resumen del Proyecto
Este repositorio documenta la ejecución de pruebas y el reporte de errores correspondientes al flujo de selección de platillos y seguimiento de pedidos. El objetivo principal fue asegurar la integridad de la lógica de negocio y la correcta visualización de la interfaz de usuario.

## Metodología y Herramientas
* Android Studio Panda 1: Uso de Layout Inspector para la validación de la jerarquía de componentes y Logcat para monitoreo de eventos.
* Jira: Documentación de defectos bajo estándares de severidad y prioridad.
* Diseño de Pruebas: Ejecución de 47 casos de prueba basados en los requisitos del producto.

## Hallazgos Críticos
Durante el ciclo de pruebas se identificaron los siguientes defectos:

1. Discrepancia de Lógica en Temporizador: El sistema muestra el tiempo estimado de entrega a domicilio en lugar del tiempo de recogida en establecimiento, contraviniendo el requisito de negocio.
2. Omisión de Componentes en UI: Mediante el uso de Layout Inspector, se confirmó la ausencia del nodo de texto para el "tiempo de preparación" en el Component Tree.
3. Superposición de Elementos: Defecto visual en la pantalla de detalles donde el nombre del restaurante interfiere con la lectura del costo y el tiempo.

## Estado Final de las Pruebas
* Casos Aprobados: 43
* Casos No Aprobados: 3
* Casos Omitidos: 2

---
Documentación técnica generada para el portafolio de QA Engineering.
