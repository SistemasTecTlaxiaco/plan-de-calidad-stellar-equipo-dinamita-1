# Plan de Calidad de Software

**Código de Versión:** V1.0  
**Fecha:** 10 de septiembre de 2025  
**Autor(es):** Equipo de Desarrollo Alfred Pay - SCF Fondo Comunitario de Stellar  

---

## 1. Introducción y Alcance

El presente documento define el **Plan de Calidad de Software** para el proyecto **Alfred Pay**, una aplicación de pagos digitales bajo la plataforma Stellar.  
El objetivo es asegurar que el producto final cumpla con los requisitos funcionales y no funcionales, así como con los más altos estándares de calidad, usabilidad, seguridad y fiabilidad, según lo establecido por el modelo **MoProSoft**.  

Este plan se aplicará a todas las fases del ciclo de vida del desarrollo de Alfred Pay, desde la planificación hasta la puesta en marcha y el mantenimiento.

---

## 2. Referencias Normativas - Modelo MoProSoft

Este plan se basa en el modelo **MoProSoft (Modelo de Procesos para la Industria del Software)**, una guía de procesos para la mejora y evaluación de procesos de desarrollo y mantenimiento de software.  

Las directrices clave del modelo que se aplicarán son:

- **Gestión de Proyectos (GPR):** Planificación, seguimiento y control de las actividades.  
- **Gestión de Recursos (GRC):** Asignación de personal y herramientas.  
- **Operación (OPE):** Desarrollo de la solución de software.  
- **Gestión de la Calidad (GCA):** Aseguramiento y control de la calidad.  

---

## 3. Gestión de la Calidad

### 3.1. Procedimientos y Actividades

- **Revisiones de Requisitos:** Reuniones periódicas con los *stakeholders* para validar y asegurar que los requisitos funcionales sean claros, completos y no ambiguos.  
- **Revisiones de Diseño:** Inspecciones del diseño arquitectónico y de la interfaz de usuario para garantizar coherencia con los requisitos y estándares de usabilidad.  
- **Inspecciones de Código (Peer Review):** Revisiones cruzadas del código fuente para identificar y corregir errores, vulnerabilidades y malas prácticas.  
- **Pruebas de Software:**  
  - *Pruebas Unitarias:* Cada componente de pago y lógica de negocio será probado individualmente.  
  - *Pruebas de Integración:* Verificación de interacción entre módulos de pagos, cartera digital y blockchain de Stellar.  
  - *Pruebas de Sistema:* Validación del sistema completo contra los requisitos de negocio.  
  - *Pruebas de Seguridad:* Pruebas de penetración y escaneo de vulnerabilidades.  
  - *Pruebas de Usabilidad:* Evaluación de la facilidad de uso para usuarios finales.  
- **Control de Cambios:** Todo cambio en requisitos, diseño o código seguirá un proceso formal de solicitud, evaluación, aprobación y verificación.  

### 3.2. Defectos y Errores de Software

Clasificación de defectos para priorizar su resolución:

- **Crítico (P1):** Impide el funcionamiento principal (ej. una transacción no se procesa). Corrección inmediata.  
- **Mayor (P2):** Afecta funcionalidades importantes sin bloquear el sistema (ej. historial de transacciones no actualizado).  
- **Menor (P3):** Afecta funciones no esenciales o errores cosméticos (ej. ícono no mostrado).  
- **Sugerencia (P4):** Recomendaciones de mejora en funcionalidad o usabilidad.  

### 3.3. Métricas de Calidad

Se medirán y analizarán las siguientes métricas:

- **Defectos por Línea de Código (Defect Density):** Defectos/KLOC.  
- **Tasa de Aprobación de Pruebas (Test Pass Rate):** (Pruebas Aprobadas / Totales) x 100.  
- **MTTR (Mean Time to Repair):** Tiempo promedio de corrección de defectos.  
- **Cobertura de Código (Code Coverage):** Porcentaje de código probado con unit tests.  
- **Defectos por Módulo:** Identifica los módulos más problemáticos.  

---

## 4. Roles y Responsabilidades

- **Gerente de Proyecto:** Supervisión general del plan de calidad.  
- **Ingeniero de Calidad:** Diseña y supervisa ejecución de pruebas y procedimientos.  
- **Analista de Requisitos:** Garantiza claridad y consistencia de requisitos.  
- **Equipo de Desarrollo:** Implementa el código y realiza pruebas unitarias.  
- **Equipo de Pruebas (QA):** Ejecuta pruebas de integración, sistema y seguridad; reporta defectos.  

---

## 5. Herramientas

- **Gestión de Proyectos:** Jira, Asana.  
- **Control de Versiones:** Git.  
- **Reporte de Defectos:** Jira, Trello.  
- **Automatización de Pruebas:** Selenium, Cypress.  

### 5.1. Procedimiento de Gestión de Defectos

1. **Identificación:** El equipo de QA documenta el defecto en Jira (incluyendo pasos, resultado esperado y obtenido).  
2. **Clasificación:** El gerente o líder técnico clasifica el defecto según severidad (P1–P4).  
3. **Asignación:** Se asigna a un desarrollador.  
4. **Corrección:** El desarrollador corrige el defecto.  
5. **Verificación:** Se realizan pruebas unitarias y se notifica al QA.  
6. **Cierre:** QA valida la corrección y cierra la incidencia.  

### 5.2. Glosario de Términos

- **Bug:** Error o falla en el software.  
- **Defecto:** Error encontrado durante desarrollo o pruebas.  
- **Métrica:** Indicador cuantitativo para medir calidad.  
- **MoProSoft:** Modelo de Procesos para la Industria del Software.  
- **KLOC:** Miles de Líneas de Código.  

---

## 6. Conclusión

El plan de calidad de **AlfredPay** asegura que el proyecto cumpla con los estándares de confiabilidad, seguridad y usabilidad que exige el ecosistema de Stellar.  

Se centra en establecer procesos claros de desarrollo, pruebas y mejora continua, garantizando que la aplicación sea robusta, escalable y fácil de usar para la comunidad.  

Al aplicar métricas de desempeño, revisiones de código y validaciones de seguridad, se busca minimizar riesgos y ofrecer una experiencia confiable en transacciones descentralizadas.  

En conclusión, el plan de calidad no solo fortalece la confianza de los usuarios y la comunidad, sino que también contribuye a la **sostenibilidad y éxito** del proyecto dentro del Fondo Comunitario de Stellar.
