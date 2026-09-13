# 🐱 Felimiau — Tienda Especializada para Felinos
### Desarrollo Frontend I (PFY2201) — Actividad Formativa Semana 4
> **Objetivo de la actividad:** Implementar componentes y utilidades del framework **Bootstrap 5.3** para construir una estructura web moderna, accesible y completamente responsiva mediante diseño *Mobile-First*.

---

## 🌐 Enlaces del Proyecto

* **Repositorio en GitHub:** [https://github.com/Lybern/PFY2201_Bootstrap_Semana4](https://github.com/Lybern/PFY2201_Bootstrap_Semana4)
* **Sitio Web en Vivo (GitHub Pages):** [https://Lybern.github.io/PFY2201_Bootstrap_Semana4/](https://Lybern.github.io/PFY2201_Bootstrap_Semana4/)

---

## 📋 Resumen del Desarrollo Realizado

En este proyecto se desarrolló la tienda virtual **"Felimiau"**, aplicando buenas prácticas de desarrollo frontend, maquetación semántica en HTML5 y los siguientes componentes principales de Bootstrap 5:

### 1. 🔗 Vinculación Oficial de Bootstrap 5.3
* **CSS:** Enlazado vía CDN oficial en la cabecera `<head>`.
* **JavaScript Bundle:** Enlazado antes del cierre de `</body>` (incluye la librería **Popper.js** para la interactividad de menús y carruseles).

### 2. 🧭 Barra de Navegación Responsiva (`<header>` / `<nav>`)
* Componente `navbar navbar-expand-lg navbar-dark bg-dark sticky-top`.
* Logotipo de la marca (`🐱 Felimiau`).
* Botón hamburguesa (`navbar-toggler`) con menú colapsable para dispositivos móviles.
* Menú desplegable (*Dropdown*) de categorías de productos.
* Formulario de búsqueda rápida alineado a la derecha.

### 3. 🎠 Carrusel de Imágenes Automático (`<section>` / `carousel`)
* Componente `carousel slide` con configuración de rotación automática cada **3 segundos** (`data-bs-interval="3000"`).
* 3 diapositivas protagonizadas por **Blanquito** (`blanquito.jpg`) y **Talia** (`talia.jpg`), más accesorios.
* Ajuste de estilo con `object-fit: contain` sobre fondo oscuro para asegurar que las fotos **nunca se corten ni distorsionen** en ningún dispositivo.
* Indicadores inferiores y controles interactivos *Anterior / Siguiente*.

### 4. 📐 Sistema de Cuadrícula Responsivo (*Grid System*)
Estructura organizada con `container`, `row` y clases responsivas por dispositivo:
* **📱 Dispositivos Móviles (`col-12`):** 1 producto por fila ($100\%$ del ancho).
* **📱 Tablets (`col-md-6`):** 2 productos por fila ($50\%$ del ancho).
* **💻 Computadoras (`col-lg-4`):** 3 productos por fila ($33.3\%$ del ancho).

### 5. 🏷️ Catálogo con Tarjetas de Contenido (`<article>` / `card`)
* 6 tarjetas con etiquetas semánticas `<article>` y clase `card h-100` para garantizar que todas mantengan la misma altura uniforme.
* Incluyen imágenes optimizadas (como el rascador castillo `rascador.png`), badges de categoría, títulos, descripciones, precios formateados y botones de acción.

### 6. 🚚 Sección de Beneficios y Servicios
* 3 columnas informativas destacando: *Envío Michi-Express*, *Calidad Felina Certificada* y *Pago 100% Seguro*.

### 7. 🦶 Pie de Página (`<footer>`)
* Pie de página semántico con información institucional, derechos reservados y autoría.

---

## 📁 Estructura del Repositorio
```text
PFY2201_Bootstrap_Semana4/
├── index.html                                      # Archivo principal para GitHub Pages
├── Carolina_Delgado_PFY2201_Bootstrap_Semana4.html # Archivo para entrega en plataforma AVA
├── blanquito.jpg                                   # Foto de Blanquito en su torre (Carrusel)
├── talia.jpg                                       # Foto de Talia en su camita (Carrusel)
├── rascador.png                                    # Foto de Rascador Castillo (Tarjeta 2)
└── README.md                                       # Documentación técnica del proyecto
```

---

## 👤 Información de Entrega
* **Estudiante:** Carolina Delgado
* **Carrera:** Analista Programador Computacional
* **Fecha:** Septiembre 2026
