# Construdata - Sistema de Gestión para Construcción

## Descripción del Proyecto
**Construdata** es una solución integral diseñada para la constructora "Edificaciones Modernas S.A.". El sistema permite la administración centralizada de proyectos de edificación, controlando desde las fases de construcción y planos técnicos hasta la gestión de inventarios, órdenes de compra, maquinaria y talento humano.

El objetivo principal es centralizar la información para permitir un seguimiento preciso del presupuesto asignado frente a los gastos reales y asegurar el cumplimiento de los cronogramas y permisos legales.

## Estructura de Módulos

El sistema está organizado en los siguientes módulos lógicos:

1.  **Módulo de Proyectos y Planificación:**
    * Gestión de Proyectos (Residencial, Comercial, Industrial).
    * Control de Fases (Excavación, Estructura, Acabados, etc.).
    * Seguimiento de porcentajes de avance y dependencias.
    
2.  **Módulo de Documentación Técnica:**
    * Catalogación de Planos (Arquitectónicos, Estructurales, Eléctricos, etc.).
    * Control de versiones y responsables técnicos.

3.  **Módulo de Logística e Inventarios:**
    * Catálogo de Materiales y proveedores.
    * Control de Stock en tiempo real y alertas de stock mínimo.
    * Gestión de Órdenes de Compra vinculadas a proyectos específicos.

4.  **Módulo de Activos y Maquinaria:**
    * Control de Maquinaria pesada (horas de uso, depreciación).
    * Gestión de Herramientas y responsables de custodia.

5.  **Módulo de Talento Humano:**
    * Registro de empleados, especialidades y certificaciones.
    * Asignación de personal a proyectos.

6.  **Módulo Financiero y Legal:**
    * Control de Presupuestos vs. Gastos Reales.
    * Gestión de Permisos Legales y alertas de vencimiento.

## Instrucciones de Uso

### 1. Visualización del Modelo UML
Para visualizar el diagrama de clases:
1.  Copie el código fuente en formato **Mermaid** proporcionado en la documentación técnica.
2.  Péguelo en [Mermaid Live Editor](https://mermaid.live/) o utilícelo en herramientas compatibles como **Eraser.io** o **Notion**.

### 2. Implementación de Clases
Las clases deben implementarse siguiendo la estructura de herencia definida para los **Activos** (Maquinaria y Herramientas) para optimizar la reutilización de código.

### 3. Registro de Datos
* **Inicio:** Registrar el Proyecto y sus Permisos Legales correspondientes.
* **Planeación:** Definir las Fases y cargar los Planos.
* **Operación:** Generar Órdenes de Compra para alimentar el Inventario y asignar Empleados al proyecto.
* **Control:** Registrar Gastos Reales conforme avancen las Fases para monitorear el presupuesto.

---
*Desarrollado para el análisis de sistemas de Edificaciones Modernas S.A.*
