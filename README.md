# 🍔 QA Testing: Urban.Lunch App - Sprint 6

¡Hola! Soy **Reynier Martin**, analista de QA en formación. [cite_start]Este repositorio contiene el trabajo realizado durante el **Sprint 6** de pruebas para la aplicación móvil **Urban.Lunch**. [cite: 1]

## 📋 Resumen del Proyecto
[cite_start]En este sprint, mi objetivo fue validar la experiencia del usuario desde la selección del punto de recogida hasta el seguimiento final del pedido. [cite: 1] Me enfoqué en asegurar que la aplicación no solo fuera funcional, sino también lógica y fácil de entender para el cliente.

### 🛠️ Herramientas y Entorno
* **Android Studio Panda 1**: Utilicé el **Layout Inspector** y **Logcat** para investigar errores que no se ven a simple vista.
* [cite_start]**Jira**: Documentación profesional de hallazgos. [cite: 2, 3]
* [cite_start]**Excel**: Seguimiento de una lista de comprobación de 47 casos de prueba. [cite: 1, 2, 3, 4]

## 🔍 Hallazgos Principales (Bugs)
Durante las pruebas, identifiqué fallos importantes que fueron reportados en Jira:

1. [cite_start]**Error de Lógica en Temporizador**: La app muestra el tiempo para "entrega a domicilio" cuando el usuario eligió "recogida en tienda". [cite: 3]
2. **Omisión de Componentes**: Gracias al **Layout Inspector**, descubrí que el "tiempo de preparación" no aparece porque el elemento no existe en el código visual (`Component Tree`).
3. [cite_start]**Defecto de Interfaz (UI)**: El nombre del restaurante se superpone con el precio, dificultando la lectura. [cite: 2]

## 📊 Estado de las Pruebas
[cite_start]De acuerdo con mi hoja de resultados[cite: 1, 2, 3]:
* [cite_start]**Casos Aprobados**: La mayoría del flujo principal (selección de mapa, botones de cantidad y navegación). [cite: 1]
* [cite_start]**Casos No Aprobados**: 3 (Relacionados con visualización de datos y lógica de tiempos). [cite: 2, 3]
* [cite_start]**Casos Omitidos**: 2 (Por falta de acceso a geolocalización o datos de distancia). [cite: 1, 3]

---
*Este proyecto es parte de mi formación como QA Engineer, demostrando habilidades en análisis técnico y documentación.*
