# 🌍 TripFungus - Sistema de Firma Digital para RGPD

Bienvenido al repositorio oficial del proyecto de digitalización de firmas para la agencia de viajes **TripFungus**. Este proyecto implementa una solución web para la firma manuscrita de la Política de Protección de Datos en dispositivos táctiles (tablets).

---

## 🎯 Objetivo del Proyecto
El objetivo principal es eliminar el uso de papel en la firma de documentos legales de la agencia. Hemos desarrollado una solución que permite:
1.  **Mostrar** el texto legal de Protección de Datos al cliente.
2.  **Capturar** la firma manuscrita del cliente directamente en pantalla.
3.  **Generar/Guardar** el documento firmado para su custodia segura.

> Este desarrollo responde a la necesidad de modernizar la gestión documental de la agencia

## 👥 Equipo de Desarrollo
* **Carlos Saelices Pérez**
* **Andrea Terol Donís**
* **Raúl Escobar Tovar**

---

## 🛠️ Solución Técnica Elegida: Desarrollo Web Propio
Tras investigar soluciones comerciales como *Adobe Sign* o *DocuSign* (ver comparativa en `docs/investigacion.md`), el equipo decidió desarrollar una **Web App personalizada**.

### ¿Por qué esta decisión?
* **Integración:** Se integra perfectamente en el ecosistema de TripFungus.
* **Coste:** Eliminamos costes recurrentes de licencias de terceros.
* **Experiencia:** Interfaz limpia diseñada específicamente para el flujo de venta de la agencia.

### Tecnologías utilizadas
* **HTML5:** Estructura semántica del documento legal.
* **CSS3:** Estilos corporativos de TripFungus y diseño responsive para tablet.
* **JavaScript (Canvas API):** Lógica para el trazo de la firma digital a mano alzada.

---

## 🔄 Flujo de Trabajo en GitHub
Para la gestión del proyecto hemos seguido una metodología ágil utilizando las herramientas de GitHub.

1.  **GitHub Projects (Kanban):** Hemos organizado las tareas en columnas (Todo, In Progress, Done) para gestionar la investigación, diseño y codificación.
2.  **Ramas:**
    * `main`: Versión estable y final del producto.
    * `investigacion`: Rama utilizada para la comparativa de software.
    * `desarrollo`: Rama donde se ha programado el código fuente de la web.
    * `documentacion`: Rama para la redacción de manuales y justificaciones.
---

## 📂 Estructura del Repositorio y Ramas

Actualmente, el proyecto sigue un flujo de trabajo basado en ramas. Los archivos se han desarrollado en paralelo y finalmente se centralizan en la rama principal.
Así es como se organiza nuestro código según su rama de origen:

```text
/
├── src/                   # (Rama 'desarrollo') Código fuente de la web
│   ├── index.html
│   └── politicaDatos.html # Implementación de la Firma digital
├── docs/                  # Documentación del proyecto
│   ├── investigacion.md   # (Rama 'investigacion') Comparativa de herramientas
│   └── decision.md        # (Rama 'documentacion') Justificación técnica
└── README.md              # (Rama 'main') Visión general del proyecto
```

---

## 📂 Estructura Final del Repositorio
Despues de hacer el 'merge' de todo, el código y la documentación se organizan de la siguiente manera:

```text
/
├── src/                   # (Rama 'desarrollo') Código fuente de la web
│   ├── index.html
│   └── politicaDatos.html # Implementación de la Firma digital
├── docs/                  # Documentación del proyecto
│   ├── investigacion.md   # Comparativa de herramientas de mercado
│   └── decision.md        # Justificación del desarrollo propio
└── README.md              # Este archivo

## LINK DE LA PÁGINA DE TRIPFUNGUS 🍄🍄‍🟫: https://scarlosdev.github.io/Implementacion-de-Firma-Digital-TripFungus/src/
