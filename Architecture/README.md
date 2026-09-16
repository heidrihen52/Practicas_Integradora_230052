# Práctica 2: Boceto de Arquitectura de Proyecto Integrador con Archify

## Descripción
En esta práctica se realizó la instalación y configuración del agente de modelado arquitectónico **Archify**, integrado con la herramienta de inteligencia artificial **Codex CLI**. Mediante la especificación del *stack* tecnológico del proyecto integrador, se generó un diagrama de arquitectura interactivo en formato HTML autónomo, mostrando capas de autenticación, cliente móvil, API, bases de datos, servicios externos e infraestructura de desarrollo.

## Objetivo
Instalar, configurar y ejecutar el agente de modelado **Archify** en conjunto con **Codex AI** para diseñar, visualizar y desplegar un diagrama de arquitectura interactivo que modele la infraestructura y flujo de datos del Proyecto Integrador.

---

## Actividades Realizadas

1. **Instalación y Configuración del Entorno:**
   * Instalación global de **Codex CLI** mediante `npm`.
   * Registro del *skill* de **Archify** (`tt-a1i/archify`) en el entorno de agentes.
2. **Generación del Modelado Arquitectónico:**
   * Ejecución de Codex CLI en la raíz del proyecto.
   * Procesamiento de especificaciones de capas, componentes y límites de confianza (*trust boundaries*).
   * Compilación del diagrama interactivo generado en un archivo HTML autónomo.
3. **Publicación y Documentación:**
   * Almacenamiento de la documentación formal en formato PDF dentro de la carpeta `Docs/`.
   * Configuración y despliegue del diagrama interactivo en **GitHub Pages**.

---

## Componentes Modelados del Sistema

* **Mobile Client:** Aplicación móvil desarrollada en Flutter.
* **Authentication Layer:** Servidor de autenticación y gestión de identidad con **Keycloak**.
* **API Layer:** Servicios Web RESTful con **FastAPI**.
* **Data Layer:** 
  * **PostgreSQL:** Base de datos relacional para datos estructurados.
  * **MongoDB:** Base de datos NoSQL para datos de documentos/logs.
* **External Services:** Servicio de mapas interactivos con **Leaflet**.
* **Development Infrastructure:** Contenedores con **Docker** y orquestación con **Docker Compose**.
* **Source Control:** Control de versiones con **Git** y **GitHub**.

---

## Resultados y Documentación

Explora la arquitectura generada y la documentación del proyecto a través de los siguientes enlaces:

### Enlaces del Proyecto

* [Ver Diagrama Interactivo de Arquitectura en GitHub Pages](https://heidrihen52.github.io/Practicas_Integradora_230052/)
* 📄 [Ver Documentación Oficial (Practica02.pdf)](./Docs/Practica02.pdf)
* 🔗 [Descargar PDF desde GitHub Pages](https://heidrihen52.github.io/Practicas_Integradora_230052/Docs/Practica02.pdf)

