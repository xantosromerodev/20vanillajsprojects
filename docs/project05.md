# EP05: DOM Array Methods

<link rel="stylesheet" href="/css/style.css">

<div class="carousel-container">

  <input type="radio" name="carousel" id="slide1" checked>
  <input type="radio" name="carousel" id="slide2">
  <input type="radio" name="carousel" id="slide3">

  <div class="carousel-slide">
    <img src="/images/project05/01.png" alt="Imagen 1">
    <img src="/images/project05/02.png" alt="Imagen 2">
    <img src="/images/project05/03.png" alt="Imagen 3">
  </div>

  <div class="carousel-nav">
    <label for="slide1">●</label>
    <label for="slide2">●</label>
    <label for="slide3">●</label>
  </div>
</div>

---

## 1️⃣ Acerca del reto

En este reto vas a construir una pequeña app que simula una lista de personas ricas. Podrás:

- Agregar personas con dinero aleatorio 💰
- Duplicar su fortuna 📈
- Mostrar solo millonarios 💵
- Ordenarlos por riqueza 🥇
- Calcular la riqueza total 🧮

Todo esto lo harás usando métodos de arrays y manipulando el DOM en tiempo real. Es uno de esos retos que parecen un juego, ¡pero te enseñan muchísimo!

---

## 2️⃣ Habilidades a reforzar

- Manipulación avanzada del DOM
- Uso de los métodos `.map()`, `.filter()`, `.sort()` y `.reduce()`
- Actualización dinámica de interfaces
- Creación de estructuras de datos con objetos
- Formateo de números como divisas con `.toLocaleString()`
- Pensamiento lógico para transformar y visualizar datos

---

## 3️⃣ Estructura de carpetas

Aquí tienes la organización recomendada:

```md
dom-array-methods/
│
├── index.html
├── style.css
├── script.js
└── readme.md
```

Opcional: puedes usar [Random User API](https://randomuser.me/) para generar nombres aleatorios si quieres ir más allá.

---

## 4️⃣ Nivel de dificultad

🏎️ Intermedio

Ya no es solo crear botones y eventos… aquí vas a manipular datos en tiempo real, pensar cómo estructurarlos y cómo modificarlos sin perder el control. ¡Es un mini-proyecto tipo dashboard real!

---

## 5️⃣ Tips

- Usa un array llamado `users` para almacenar cada persona y su dinero.
- Cada vez que hagas una acción (agregar, filtrar, ordenar...), actualiza el DOM.
- Usa `map()` para transformar los datos sin mutar el array original.
- `filter()` es perfecto para mostrar solo millonarios.
- `reduce()` te dará la suma total de la riqueza.
- Usa `Intl.NumberFormat` o `.toLocaleString('en-US', {style: 'currency', currency: 'USD'})` para mostrar bien los valores 💵.

---

## 6️⃣ Bonus

- 🧓 Agrega fotos o nacionalidades con Random User API
- 📱 Hazlo responsive con flexbox o grid
- 🎨 Muestra gráficamente el crecimiento de la riqueza con una barra o círculo
- 🕹️ Agrega animaciones con cada acción
- 💾 Guarda el estado con localStorage para mantener los datos al recargar

---

## 7️⃣ Comunidad

Este reto es perfecto para compartir cómo usas los métodos más usados de JavaScript:

- 📸 Publica un video o captura mostrando cómo se transforma el array
- 🤯 Cuéntanos en Discord qué fue lo más difícil de entender
- 🔄 Propón nuevas acciones como “repartir la riqueza” o “eliminar usuarios”

👉 **[ÚNETE A LA COMUNIDAD EN WHATSAPP](https://chat.whatsapp.com/CldsuiaJ52t3NvDg47zaWP)**

---

> ""Cada línea de código te acerca a tu sueño." ✨👨‍💻"