# 🎮 Tetris – Vanilla JS Edition

Un **Tetris 100% en HTML, CSS y JavaScript puro**, sin dependencias, diseñado para jugar directamente en el navegador.  
Incluye interfaz moderna, vista previa de pieza siguiente, controles de teclado y soporte básico para móviles.

![Tetris Screenshot](./screenshot.png)

---

## 🚀 Características

- **HTML + CSS + JavaScript** puro (sin frameworks).
- **Controles de teclado y táctiles** para escritorio y móvil.
- **Vista previa** de la siguiente pieza.
- **Puntaje, líneas y nivel** con aumento progresivo de dificultad.
- **Sistema de bolsa aleatoria** para piezas (random bag).
- **Pausa y reinicio rápido** (`P` y `R`).
- **Sombra de caída (ghost piece)**.
- Diseño responsive y adaptado a pantallas pequeñas.

---

## 📂 Estructura

El proyecto está contenido en **un único archivo HTML**, que incluye:
- Etiquetas `<style>` para los estilos.
- Etiquetas `<script>` para la lógica del juego.
- Elementos `<canvas>` y `<aside>` para el tablero y la interfaz.

---

## 🕹 Controles

### Teclado
| Tecla       | Acción                |
|-------------|-----------------------|
| ← / →       | Mover pieza           |
| ↓           | Caída suave           |
| ↑           | Rotar pieza           |
| Espacio     | Caída dura             |
| P           | Pausar / Reanudar     |
| R           | Reiniciar partida     |

### Móvil
- Botones virtuales para mover, rotar y soltar la pieza.
- Soporte táctil básico.

---

## 📦 Instalación y uso

1. **Descarga o clona** este repositorio:
   ```bash
   git clone https://github.com/TU-USUARIO/tetris-js.git
   ```
2. Abre el archivo `index.html` en tu navegador.
3. ¡Empieza a jugar!

---

## 📌 Mejoras planeadas
- ✅ **Hold** (guardar pieza para usar después).  
- ✅ **Tabla de high scores** con `localStorage`.  
- ✅ **Sonidos** para rotar, colocar pieza y borrar líneas.  
- ⏳ **Modo versus** (dos tableros en pantalla).  
- ⏳ **Skin retro** estilo Game Boy.

---

## 📝 Licencia

Este proyecto se distribuye bajo la licencia **MIT**.  
Eres libre de usar, modificar y distribuir este código, siempre dando crédito al autor original.

---

## ❤️ Créditos

Desarrollado por Armando Tapia, con apoyo de GPT‑5.  
Inspirado en la mecánica clásica de Tetris® (marca registrada por The Tetris Company).
