# Proyecto Ratón Lúdico

**Ratón Lúdico** es un blog dedicado a las reseñas y noticias sobre juegos indie, con especial énfasis en géneros como los juegos de rol y el terror psicológico. Nuestro objetivo es explorar y destacar títulos independientes que ofrecen experiencias únicas y emocionantes, muchas veces pasados por alto en la industria principal. Si eres un apasionado de los juegos indie, este blog es tu espacio para descubrir y profundizar en ellos.

---

## Diseño de la página

El diseño de Ratón Lúdico está inspirado en una estética moderna y elegante con predominancia de tonos púrpuras y un modo oscuro por defecto, que brinda una experiencia visual cómoda y envolvente para los usuarios. 

- Uso de gradientes suaves y sombras para dar profundidad.
- Animaciones sutiles para mejorar la interacción y dinamismo.
- Diseño responsivo para una correcta visualización en dispositivos móviles y de escritorio.
- Integración de un reproductor de música para ambientar la experiencia en las páginas de reseñas.
- Navegación clara y accesible con un toggle para cambiar entre modo oscuro y claro.

---

## Lenguajes utilizados

- **HTML** con plantillas Jinja2 (Flask) para la generación dinámica de contenido.
- **CSS** moderno con variables CSS para temas claros y oscuros, animaciones y diseño responsivo.
- **JavaScript** para funcionalidades interactivas, como el reproductor de música.
- **Python (Flask)** para el backend y manejo de rutas (implícito por el uso de `url_for` en las plantillas).

---

## Cómo ejecutar de forma local

Sigue estos pasos para ejecutar el proyecto en tu máquina local:

1. **Clonar el repositorio**
git clone https://github.com/lunahkq/ratonludico.git
cd raton-ludico

2. **Crear y activar un entorno virtual (opcional pero recomendado)**
python -m venv venv
source venv/bin/activate # En Windows: venv\Scripts\activate

3. **Instalar dependencias**
  Asegúrate de tener Flask instalado. Si tienes un `requirements.txt`, instala con: pip install -r requirements.txt
  Si no, instala Flask directamente: pip install Flask

4. **Ejecutar la aplicación**
  Ejecuta el archivo index.py directamente con Python:python index.py
  Esto iniciará el servidor Flask.

5. **Abrir en el navegador**
  Ve a `http://127.0.0.1:5000` para ver la página en local.

---

## Créditos

- **Desarrollo y diseño:** Fabiana Rodríguez, Miguel SOlorzano, Samuel Jiménez, Yeismar Ruíz
- **Inspiración:** Comunidad de juegos indie y del terror psicológico.
- **Imágenes y recursos:** Todas las imágenes y audios están alojados en la carpeta `static/` y son propiedad de sus respectivos creadores o están bajo licencias libres para uso educativo y de reseñas.
- **Iconos:** Uso de [Font Awesome](https://fontawesome.com/) para iconografía.
- **Framework:** Flask para backend y Jinja2 para plantillas.

---

¡Gracias por visitar al Ratón Lúdico! 🎮🐭
