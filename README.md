# 🍲 Buscador de Recetas con Favoritos

Aplicación web desarrollada en **JavaScript puro**, **Bootstrap** y la API gratuita de [TheMealDB](https://www.themealdb.com/api.php).  
Permite buscar recetas por categorías, ver los detalles en un **modal** y guardar recetas en **favoritos** usando `localStorage`.

Este proyecto fue creado como parte del curso de Udemy:  
[JavaScript Moderno: Guía Definitiva Construye +10 Proyectos](https://www.udemy.com/course/javascript-moderno-guia-definitiva-construye-10-proyectos)

---

## 🚀 Funcionalidades

- **Búsqueda por categoría:** las categorías se obtienen dinámicamente desde la API.
- **Listado de recetas:** muestra imagen, nombre y un botón para ver detalles.
- **Modal con detalles de receta:**
  - Imagen
  - Instrucciones
  - Ingredientes y cantidades
  - Botón para guardar o eliminar de favoritos
- **Sistema de favoritos con localStorage:**
  - Guardar recetas favoritas
  - Eliminar favoritos
  - Persistencia entre sesiones
- **Página de favoritos:** muestra todas las recetas guardadas localmente.
- **Mensajes dinámicos:** si no hay favoritos, se muestra un mensaje indicándolo.
- **Toast de Bootstrap:** confirma la acción al guardar o eliminar una receta.

---

## 🛠️ Tecnologías utilizadas

- **HTML5** – Estructura de la app
- **CSS3** – Estilos y clases de Bootstrap
- **JavaScript (ES6+)** – Lógica, manejo de eventos y localStorage
- **Bootstrap 5** – Estilos, modal y toasts
- **TheMealDB API** – Fuente de datos de recetas

---

## 🚀 Cómo usar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/LucreciaVeron/Proyecto-BuscarRecetas.git
