# Juegos incluidos

## ¡BOOM CÓSMICO! — Versión Python (`juegopicante.py`)

Juego arcade espacial desarrollado en **Pygame**. El jugador controla una nave (cohete) con las flechas del teclado para recolectar estrellas y completar constelaciones mientras esquiva asteroides y meteoritos.

**Características:**
- 12 constelaciones para completar (Orión, Osa Mayor, Leo, etc.)
- Sistema de puntuación con combo y multiplicador
- 4 potenciadores: Escudo, Slow-Mo, Vida extra, Multiplicador x2
- Niveles progresivos con modo furia al acabarse el tiempo
- Efectos de partículas, estelas de fuego, nebulosas animadas
- Menú de login con tabla de puntuaciones históricas (top 5)
- Sonidos y música ambiente
- Requiere Python + Pygame para ejecutarse

---

## ¡BOOM CÓSMICO! — Versión Web (`juegopicante.html` / `index.html`)

Port del juego original a **HTML5 + Canvas + JavaScript**, sin dependencias externas. Un solo archivo que se abre en cualquier navegador moderno.

**Características:**
- Misma jugabilidad que la versión Python
- Renderizado por Canvas 2D
- Sonidos sintetizados con Web Audio API (sin archivos externos)
- Puntuaciones guardadas en `localStorage`
- **Controles táctiles** para dispositivos móviles:
  - Joystick virtual para movimiento
  - Botones de acción (Espacio y Pausa)
  - Botón de pantalla completa
- Orientación horizontal forzada en móviles
- Escalado automático a resolución 1280×720

**Cómo jugar:**
- Abrir `juegopicante.html` (o `index.html`) en cualquier navegador
- Ingresar un nombre y presionar "Jugar"
- En PC: flechas del teclado para mover, P para pausar, Espacio para empezar/reiniciar
- En móvil: joystick táctil, botón ▶ para empezar, ⏸ para pausar

---

*Hecho por Benja Basiluk — Escuela Superior El Nacional, Desarrollo de Software*
