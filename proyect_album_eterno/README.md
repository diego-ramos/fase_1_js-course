# 🦄 Mi Crypto-Álbum Eterno

¡Bienvenido a tu proyecto paralelo del curso!
A lo largo de las 4 semanas, construirás una aplicación web para coleccionar tus stickers favoritos de internet.

**Objetivo:** Crear una web donde puedas pegar URLs de imágenes y verlas aparecer en tu álbum personal.

---

## 📅 Plan de Trabajo

Este proyecto es **incremental**. No intentes hacerlo todo el primer día. Sigue el ritmo del curso.

### 🔹 Semana 1: El Esqueleto (HTML)
**Objetivo:** Crear la estructura visual.
1. Abre `index.html`.
2. Crea un título `<h1>` llamativo.
3. Crea un formulario `<form>` con:
   - Un `input` para el nombre del sticker.
   - Un `input` para la URL de la imagen.
   - Un botón `<button>` que diga "Pegar en el Álbum".
4. Crea un `div` vacío con id `album-grid` donde vivirán los stickers.

### 🔹 Semana 2: La Magia (DOM y Eventos)
**Objetivo:** Hacer que el botón funcione.
1. Abre `script.js`.
2. Selecciona tus inputs y botón usando `document.getElementById`.
3. Agrega un `addEventListener` al botón.
4. Cuando se haga clic:
   - Lee el texto de los inputs.
   - Crea un nuevo elemento `div` usando `document.createElement`.
   - Ponle el nombre del sticker como texto.
   - Agrégalo al `album-grid` usando `appendChild`.

### 🔹 Semana 3: Memoria (Arrays y Loops)
**Objetivo:** Guardar los datos de forma ordenada.
1. Crea un array vacío `let album = []`.
2. Al hacer clic, en lugar de crear el div directamente:
   - Crea un objeto con los datos: `{ nombre: "...", url: "..." }`.
   - Agrega ese objeto al array `album`.
3. Crea una función `renderAlbum()` que:
   - Limpie el grid (`innerHTML = ''`).
   - Recorra el array con un bucle `for`.
   - Por cada elemento del array, cree el HTML y lo muestre.

### 🔹 Semana 4: El Álbum Final (Objetos y Estilos)
**Objetivo:** Que se vea increíble.
1. Modifica tu función `renderAlbum`.
2. Ahora, por cada sticker, crea una tarjeta completa:
   - Un `img` con la URL (`src`).
   - Un `h3` con el nombre.
3. ¡Disfruta de tu colección!

---

## 🎨 Estilos
El archivo `style.css` ya está listo y conectado. A medida que uses las clases correctas (como `.container`, `.sticker-card`), ¡tu web se verá profesional automáticamente!
