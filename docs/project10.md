# EP10: Music Player

<link rel="stylesheet" href="/assets/css/carousel.css">

<div class="carousel-container">

  <input type="radio" name="carousel" id="slide1" checked>
  <input type="radio" name="carousel" id="slide2">

  <div class="carousel-slide">
    <img src="/images/project10/01.png" alt="Imagen 1">
    <img src="/images/project10/02.png" alt="Imagen 2">
  </div>

  <div class="carousel-nav">
    <label for="slide1">●</label>
    <label for="slide2">●</label>
  </div>
</div>

--- 

## 1️⃣ Acerca del reto

En este reto vas a crear tu propio reproductor de música en la web. Tendrás botones para reproducir, pausar, avanzar o retroceder canciones, y mostrarás la carátula del disco de manera visual y atractiva.

Este proyecto es ideal para practicar cómo controlar elementos multimedia con JavaScript y crear interfaces modernas e interactivas.

---

## 2️⃣ Habilidades a reforzar

Con este reto vas a mejorar en:

- Control de audio con JavaScript (`play()`, `pause()`, `currentTime`, etc.)
- Manipulación del DOM y eventos de botones
- Ciclos para navegar por un array de canciones
- Diseño responsive y estilización con CSS
- Manejo de clases activas para animaciones o cambios de estado

---

## 3️⃣ Estructura de carpetas

```md
music-player/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   ├── images/
│   │   └── cover.jpg          # imagen del álbum o portada
│   └── music/
│       ├── track1.mp3         # pista de audio principal
│       └── track2.mp3         # otra pista (opcional)
└── README.md                  # documentación del reto
```

---

## 4️⃣ Nivel de dificultad

🟡 Intermedio

Ideal si ya dominas lo básico y quieres practicar cómo crear una experiencia interactiva real con HTML, CSS y JavaScript.

---

## 5️⃣ Tips

Buenas prácticas y sugerencias:

- Usa un array de objetos para tus canciones, incluyendo `title`, `src` del audio y `cover` de la imagen.
- Controla el estado: canción actual, si está reproduciendo o en pausa.
- Usa clases para mostrar visualmente qué canción está activa.
- Puedes rotar la imagen del disco mientras suena, usando CSS y clases dinámicas.
- Asegúrate de que el audio se reinicie al cambiar de canción.

---

## 6️⃣ Bonus

¿Quieres ir más allá? Aquí tienes algunas ideas:

- Muestra el nombre de la canción y el artista.
- Agrega una barra de progreso con el tiempo actual y total.
- Permite que el usuario suba sus propios archivos de música.
- Crea una playlist donde el usuario pueda seleccionar la canción.
- Hazlo compatible con dispositivos móviles (responsive + touch).

---

## 7️⃣ Comunidad

¿Tienes dudas con tu código? ¿Te atascaste en un reto? ¿Te gustaría compartir tus avances o conocer cómo otros están resolviendo los mismos desafíos?

Aprender a programar puede ser solitario a veces, pero no tiene por qué serlo. En nuestra comunidad de WhatsApp encontrarás personas como tú: curiosas, apasionadas por la tecnología, y con ganas de aprender y mejorar cada día.

🚀 **¿Qué ganas al unirte?**

- Recibir apoyo cuando te bloquees
- Compartir tus avances y obtener feedback
- Conocer a otros estudiantes y motivarte
- Participar en retos, dinámicas y actividades grupales

👉 **[ÚNETE A LA COMUNIDAD EN WHATSAPP](https://chat.whatsapp.com/CldsuiaJ52t3NvDg47zaWP)**

---

> “La música es poderosa. Y cuando tú construyes algo que reproduce música… tú también te vuelves poderoso.”