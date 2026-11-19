# Análisis y Especificación de Requerimientos - ERP de Stock

Trabajo universitario sobre relevamiento y modelado de requerimientos para el desarrollo de un sistema de gestión de inventario, basado en el caso real de una empresa constructora y electromecánica (*CR Construcciones*).

El objetivo del proyecto fue identificar cuellos de botella en la logística operativa entre depósitos y obras, y diseñar la especificación funcional para una solución de software escalable.

## 📌 Contexto del Negocio y Problemática
* **Cliente:** PyME del sector construcción y mantenimiento electromecánico.
* **Desafío:** La empresa operaba con gestión manual de inventarios, sin sincronización entre el depósito central (Guernica) y los puntos de obra (CABA). Esto generaba compras duplicadas por urgencia, desfasajes de stock y demoras operativas.
* **Solución Propuesta:** Diseño de un Sistema ERP (SaaS) centralizado, con flujos de autorización automatizados, alertas de faltantes y sincronización offline/online para su uso en zonas de obra.

## 🛠️ Entregables y Metodología
Durante el proceso de ingeniería de requerimientos, se desarrollaron los siguientes artefactos:
1. **Elicitación:** Entrevistas a *stakeholders* y análisis del dominio mediante relevamiento documental (análisis de facturas y remitos físicos).
2. **Modelado de Reglas de Negocio:** Definición de roles (Admin, Capataz, Gerencia) y matrices de trazabilidad.
3. **Especificación Funcional (SRS):** 
   * Casos de Uso del Sistema (ej. ABM de materiales, registro de egreso a obra, autorización de compras).
   * Historias de Usuario estructuradas.
   * Identificación de Requerimientos No Funcionales (SaaS, concurrencia, tolerancia a desconexión).
4. **Validación:** Diseño de wireframes y prototipos interactivos para validar flujos de pantalla.

## 📄 Documentación Completa
El documento completo de especificación (incluyendo flujos alternativos, manejo de excepciones y análisis detallado de stakeholders) está disponible para su consulta:

**[Especificación de Requerimientos Completa (PDF)](./Proyecto_analisis_de_requerimientos_ERP_Construcciones.pdf)**

---
*Este proyecto fue desarrollado de forma colaborativa (equipo de 4 integrantes) como trabajo práctico integrador para la asignatura Sistemas de Información II (UADE).*
