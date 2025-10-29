El sitio web está compuesto por tres páginas (o secciones) principales, todas con un diseño **Mobile First** y completamente adaptable a cualquier dispositivo:

* **Inicio (`index.html`):** Presentación del taller e introducción con un pequeño video.
* **Cursos (`cursos.html`):** Catálogo de talleres con uso de tablas  y contenido estructurado.
* **Contacto (`contacto.html`):** Formulario de contacto avanzado.

### Tecnologías Empleadas

| **HTML5 (Semántico)** | Estructura del contenido usando elementos como `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<figure>`, `<article>`, y `<form>`. |
| **CSS3** | Diseño, tipografía, espaciado, y cumplimiento de los estándares de accesibilidad. |
| **Diseño Responsive** | Adaptación completa a **Desktop**, **Tablet** y **Mobile** mediante `Media Queries`. |

---

## 🚀 Despliegue y Visualización

Para visualizar el proyecto localmente, sigue estos pasos:

1.  **Clona el repositorio:**
    ```bash
    git clone [https://docs.github.com/es/repositories/creating-and-managing-repositories/quickstart-for-repositories](https://docs.github.com/es/repositories/creating-and-managing-repositories/quickstart-for-repositories)
    ```
2.  **Abre la carpeta:** Navega hasta el directorio `el-rincon-del-costurero`.
3.  **Abre con Live Server:** Recomendamos usar la extensión **Live Server** de Visual Studio Code. Haz clic derecho en `index.html` y selecciona "Open with Live Server" para ver el sitio en tu navegador.

---
## 🛠️ Estructura del Proyecto

El proyecto sigue una organización clara y modular para facilitar la gestión de los archivos HTML, los estilos CSS y los recursos (imágenes y videos).

```
el-rincon-del-costurero/
├── index.html            <-- Página de Inicio
├── cursos.html           <-- Catálogo de Cursos
├── contacto.html         <-- Formulario y Ubicación
├── README.md             <-- Documentación principal (Este archivo)
├── CSS/
│   └── style.css         <-- Hoja de estilos principal (CSS Responsive)

├── VIDEOS        <-- Video del Index.html
├── IMAGENES      <-- Imagenes de las distinas paginas
├── PDF           <-- PDF descargable de la pagina de cursos.html
└── avanzado.jpg   <-- Imagen para Curso Avanzado
