# EP04: Exchange Rate Calculator

<link rel="stylesheet" href="/css/style.css">

<div class="carousel-container">

  <input type="radio" name="carousel" id="slide1" checked>
  <input type="radio" name="carousel" id="slide2">
  <input type="radio" name="carousel" id="slide3">

  <div class="carousel-slide">
    <img src="/images/project04/01.png" alt="Imagen 1">
    <img src="/images/project04/02.png" alt="Imagen 2">
    <img src="/images/project04/03.png" alt="Imagen 3">
  </div>

  <div class="carousel-nav">
    <label for="slide1">●</label>
    <label for="slide2">●</label>
    <label for="slide3">●</label>
  </div>
</div>

---

## 1️⃣ Acerca del reto

En este reto vas a crear un conversor de divisas en tiempo real usando HTML, CSS y JavaScript. Podrás seleccionar monedas, ingresar un monto y ver el equivalente automáticamente. Además, incluye un botón para intercambiar las monedas. 🪙🔄

Ideal para entender cómo funcionan las API externas en proyectos reales. ¡Ya estás hablando con servicios del mundo real!

---

## 2️⃣ Habilidades a reforzar

- Consumo de APIs externas (fetch)
- Lectura y parseo de JSON
- Lógica condicional y manejo de eventos
- Actualización dinámica del DOM
- Interacción entre múltiples inputs y selects
- Precisión con decimales y conversiones monetarias

---

## 3️⃣ Estructura de carpetas

Tu proyecto debe estar organizado así:

```md
exchange-rate-calculator/
│
├── index.html
├── style.css
├── script.js
└── readme.md
```

Puedes usar una API como [ExchangeRate-API](https://www.exchangerate-api.com/) o [exchangerate.host](https://exchangerate.host/) (¡es gratuita y no requiere token!).

---

## 4️⃣ Nivel de dificultad

🏎️ Intermedio

Este reto es perfecto si ya dominas los eventos y manipulación básica del DOM. Aquí vas a integrar datos externos y eso eleva el nivel. ¡Es una introducción suave al mundo del desarrollo con APIs!

---

## 5️⃣ Tips

- Usa `fetch()` para obtener los datos desde la API.
- Recuerda validar si la respuesta fue exitosa (`res.ok`).
- Redondea el resultado con `.toFixed(2)` para mostrar centavos.
- Usa `addEventListener('input', ...)` para reaccionar en tiempo real.
- El botón “Swap” puede intercambiar los valores con una simple variable temporal.

---

## 6️⃣ Bonus

🔥 Si quieres mejorar aún más el reto:

- 🕒 Muestra la última fecha de actualización del tipo de cambio.
- 📱 Haz el diseño responsive y que se vea bien en el celular.
- 🌐 Añade banderas o íconos junto a las monedas.
- 💾 Guarda la última moneda usada con localStorage.
- ⏳ Agrega un spinner o loader mientras se carga la conversión.

---

## 7️⃣ Comunidad

Este proyecto es súper útil y visual, así que:

- 💬 Cuéntale a la comunidad qué API usaste y por qué.
- 💡 Comparte tu diseño personalizado: ¡hazlo visualmente atractivo!
- 🧩 Experimenta con monedas raras o criptomonedas si tu API lo permite.

👉 **[ÚNETE A LA COMUNIDAD EN WHATSAPP](https://chat.whatsapp.com/CldsuiaJ52t3NvDg47zaWP)**

---

> “Cada día que programas, tu futuro se vuelve más posible. 🔥"