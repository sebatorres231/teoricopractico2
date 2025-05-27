 🏺 ¡La Figura Misteriosa del Museo en Casa! ✨

Este es un proyecto educativo interactivo diseñado para niños y niñas, que busca acercarlos a la historia y el arte precolombino a través de una experiencia divertida y creativa. Se centra en una figura de cerámica de la antigua Cultura Aguada, del Valle de Ambato, Catamarca.

El objetivo es despertar la curiosidad por la historia, fomentar la creatividad y la imaginación, y ofrecer un espacio para la expresión artística a través del coloreado digital.

## 🚀 Funcionalidades

* **Descubre los Misterios:** Toca puntos interactivos en la figura para aprender datos interesantes y curiosidades sobre sus características (nariz, ojos, boca, etc.).
* **Historias Mágicas:** Genera historias cortas y originales, creadas por inteligencia artificial (Gemini), que dan vida a la figura y su contexto cultural.
* **Pregúntale a la Figura:** Haz tus propias preguntas a la figura misteriosa y recibe respuestas imaginativas, también generadas por IA, que conectan con la Cultura Aguada.
* **¡A Colorear!:** Una sección interactiva donde los niños pueden colorear la figura con una paleta de colores y ajustar el tamaño del pincel, fomentando la expresión artística.

## 💻 Tecnologías Utilizadas

* **HTML5:** Estructura del contenido.
* **CSS3 (Tailwind CSS):** Estilos y diseño responsivo.
* **JavaScript:** Interactividad, lógica de la aplicación y manejo del Canvas.
* **Google Gemini API:** Para la generación de historias y respuestas interactivas.

## 🖼️ Archivos del Proyecto

* `index.html`: El archivo principal de la página web.
* `cara.png`: Imagen de la figura para la sección interactiva.
* `cara2.png`: Imagen de la figura para la sección de coloreado (dibujo lineal).
* `.nojekyll`: Archivo vacío crucial para el despliegue correcto en GitHub Pages, asegurando que los SVG y scripts funcionen sin conflictos con Jekyll.

## ▶️ Cómo Ver el Proyecto

1.  **Clona o Descarga el Repositorio:**
    ```bash
    git clone [https://github.com/sebatorres231/teoricopractico.git](https://github.com/sebatorres231/teoricopractico.git)
    cd teoricopractico
    ```
    O descarga el archivo ZIP del repositorio.

2.  **Asegura los Archivos de Imagen:**
    Verifica que `cara.png` y `cara2.png` estén en la misma carpeta que `index.html`.

3.  **Configura tu Clave de API de Google Gemini:**
    Para que las funcionalidades de IA (`¡Historias Mágicas!` y `¡Pregúntale a la Figura!`) funcionen, necesitas una clave de API de Google Gemini.
    * Obtén tu clave de API en [Google AI Studio](https://aistudio.google.com/).
    * Abre el archivo `index.html` en un editor de texto.
    * Busca las líneas `const apiKey = "";` (hay dos).
    * Reemplaza `""` con tu clave de API real:
        ```javascript
        const apiKey = "TU_CLAVE_DE_API_AQUI"; // ¡Pega tu clave aquí!
        ```
    * Guarda los cambios en `index.html`.

4.  **Abre en un Servidor Web (Recomendado):**
    Debido a las restricciones de seguridad de los navegadores para archivos locales, es **altamente recomendable** ejecutar este proyecto a través de un servidor web.
    * **Opción 1: GitHub Pages (Recomendado para compartir):**
        Este proyecto está configurado para ser desplegado con GitHub Pages.
        Una vez subidos todos los archivos (incluyendo el `.nojekyll` y la `apiKey` configurada) a tu rama `main` (o `master`), tu sitio estará disponible en una URL como:
        `https://sebatorres231.github.io/teoricopractico/`
        Asegúrate de que en la configuración de tu repositorio en GitHub, en `Settings > Pages`, la fuente de despliegue sea la rama `main` y la carpeta `/ (root)`.

    * **Opción 2: Servidor Local (para desarrollo):**
        Si quieres verlo localmente, puedes usar una extensión de VS Code como "Live Server" o un servidor HTTP simple. Por ejemplo, en Python:
        ```bash
        python -m http.server 8000
        ```
        Luego, abre tu navegador en `http://localhost:8000`.

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar el proyecto, encuentras un error o quieres añadir nuevas funcionalidades, no dudes en:

1.  Hacer un "fork" del repositorio.
2.  Crear una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3.  Realizar tus cambios.
4.  Abrir un "Pull Request".

---

¡Esperamos que disfrutes de esta mágica aventura con la Figura Misteriosa!
