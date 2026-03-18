# CARTELERA
APLICACIÓN SOBRE UNA CARTELERA DE CINE 
#  Proyecto de Automatización: CARTELERA

Este repositorio contiene la estrategia de pruebas y aseguramiento de calidad (QA) para la aplicación de Cartelera de Cine. Se enfoca en validar tanto el rendimiento del Front-end como la integridad de los flujos del Back-end.

## Tecnologías Utilizadas
* **Selenium IDE:** Para la automatización de pruebas funcionales (E2E).
* **Google Lighthouse:** Para auditorías de Performance, SEO y Accesibilidad.
* **GitHub:** Para el control de versiones de la evidencia.

---

## Contenido del Repositorio

### Automatización con Selenium
El archivo `CINEPLEX.side` contiene los scripts automatizados que validan los siguientes flujos críticos:
1. **Búsqueda de Películas:** Validación de integración con la API.
2. **Alta de Registros:** Prueba de persistencia en la base de datos (Guardar).
3. **Gestión de Datos (CRUD):** Flujos de edición y eliminación de películas, manejando alertas de JavaScript y esperas dinámicas (Waits).

###  Reportes de Rendimiento
En el archivo `rendimiento.pdf` se encuentra la evidencia de la auditoría de **Lighthouse**, destacando:
* **Performance:** Optimización de carga de imágenes.
* **Accesibilidad:** Cumplimiento de estándares para lectores de pantalla.
* **Best Practices:** Seguridad y uso de librerías actualizadas.

---

## Cómo ejecutar las pruebas
1. Instala la extensión de **Selenium IDE** en Chrome o Firefox.

  ## Stack de la Aplicación (SUT)
La aplicación bajo prueba (System Under Test) es una plataforma de gestión de cine desarrollada con las siguientes tecnologías:

* **Front-end:** Desarrollado con **HTML5** y **JavaScript**, utilizando una interfaz modular que incluye secciones como `agregar.html`, `editar.html`, `index.html` y `recomendaciones.html`.
* **Back-end:** Implementado con **PHP**, encargado de procesar las peticiones del servidor y la lógica de negocio.
* **Base de Datos:** Utiliza **MySQL** (identificado por la carpeta `bd/`), donde se almacena la persistencia de las películas, usuarios y configuraciones de la cartelera.
* **Arquitectura:** Una aplicación web clásica que permite operaciones CRUD (Crear, Leer, Actualizar y Borrar) interactuando directamente con el DOM y el servidor.
3. Abre la extensión y selecciona "Open an existing project".
4. Carga el archivo `CINEPLEX.side`.
5. Ejecuta el Test Suite y observa los resultados en tiempo real.


https://github.com/santijim450/CARTELERA  es el codígo fuente.
