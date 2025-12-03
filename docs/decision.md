# Decisión de Solución Técnica: Desarrollo Propio

## 1. Análisis de las opciones de mercado
Tras realizar la investigación comparativa (ver `docs/investigacion.md`), el equipo ha analizado la viabilidad de implementar soluciones comerciales como Adobe Acrobat, DocuSign o Signeasy.

Aunque estas herramientas son robustas, hemos detectado los siguientes inconvenientes para el caso de uso específico de la Agencia de Viajes "TripFungus":

* **Costes recurrentes:** Las opciones que permiten una gestión profesional y segura (como DocuSign) implican un coste mensual por licencia que incrementa los gastos fijos de la agencia.
* **Dependencia de terceros:** Al usar plataformas externas, dependemos de sus servidores y cambios en sus políticas de privacidad.
* **Experiencia de usuario fragmentada:** Obligaría al cliente a salir del entorno de la agencia para firmar en una app de terceros, rompiendo la fluidez del proceso de venta.

## 2. Solución seleccionada: Desarrollo de Aplicación Web (In-house)
El equipo de desarrollo de TripFungus ha decidido **diseñar y desarrollar una aplicación web propia** para la captura de la firma manuscrita.

Esta decisión se basa en la posibilidad contemplada en los requisitos del proyecto de "seleccionar o desarrollar" una solución

### Justificación Técnica y de Negocio

La elección de un desarrollo propio aporta las siguientes ventajas competitivas:

1.  **Integración Total (Ad-hoc):** La solución se diseñará específicamente para mostrar el texto legal y capturar la firma en el mismo flujo, sin cambiar de ventana, optimizando la experiencia en tablet.
2.  **Ahorro de Costes a Largo Plazo:** Se elimina el pago de suscripciones mensuales. El único coste es el tiempo de desarrollo inicial y el mantenimiento.
3.  **Control de los Datos:** Los documentos firmados se guardarán directamente en los sistemas de la agencia, garantizando la custodia segura sin intermediarios
4.  **Escalabilidad:** Al ser dueños del código, podremos añadir futuras funcionalidades (como enviar copia por email automáticamente) sin depender de los planes de precios de un proveedor externo.

## 3. Tecnologías a utilizar
Para llevar a cabo este desarrollo, utilizaremos tecnologías estándar de desarrollo web (Frontend):
* **HTML5/CSS3:** Para la estructura y diseño visual del documento legal.
* **JavaScript (Cliente):** Para la lógica de captura de trazado de firma.

---
**Estado de la decisión:** ✅ Aprobada
**Fecha:** 03/12/2025
**Firmado:** Equipo TripFungus
