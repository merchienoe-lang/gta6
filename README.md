# 🌴 Vice City VI — Voxel Edition (WebGL2)

Videojuego de mundo abierto en 3D con estética cúbica/voxel inspirado en **GTA VI / Vice City**, desarrollado íntegramente en **HTML5, CSS y JavaScript puro con WebGL2** en un único archivo (`index.html`), sin ninguna librería ni recurso externo.

## ✨ Características principales
- **Protagonista Jason (Voxel Art):** Modelado por piezas articuladas con su camisa vaquera abierta, camiseta gris, cadena de oro, reloj, bermudas cargo y armamento.
- **Motor WebGL2 propio:** Renderizado instanciado, Shadow Mapping PCF suave (2048x2048), iluminación direccional y puntual, agua animada y ciclo día/noche de 240s.
- **Postprocesado HDR + Bloom:** Extracción de luminancia y desenfoque gaussiano para resaltar neones rosas/turquesas, farolas y faros nocturnos.
- **Conducción y Tráfico:** Entra y sal de cualquier coche (`E`), físicas de aceleración, derrape con freno de mano (`Espacio`) y claxon (`F`).
- **Combate y Armas:** Apuntado sobre el hombro (`Clic Derecho`), disparos (`Clic Izquierdo`) y cambio entre Pistola 9mm y Subfusil (`1`/`2` o rueda del ratón).
- **Audio Procedural (Web Audio API):** Sonido de motor dinámico según velocidad, disparos sintetizados, puertas y claxon sin archivos de audio.

## 🎮 Controles
| Tecla / Acción | Función |
| :--- | :--- |
| **W A S D** | Mover a Jason / Conducir vehículo |
| **Ratón** | Girar cámara / Apuntar |
| **Shift** | Correr / Turbo en coche |
| **Espacio** | Saltar / Freno de mano (derrape) |
| **E** | Entrar o salir del vehículo más cercano |
| **Clic Derecho** | Apuntar sobre el hombro |
| **Clic Izquierdo** | Disparar |
| **1 / 2** o **Rueda** | Cambiar entre Pistola y Subfusil |
| **F** | Tocar el claxon (dentro de un coche) |
| **Esc** | Pausar / Liberar ratón |

## 🚀 Cómo jugar
- **En local:** Descarga el archivo `index.html` y ábrelo directamente con doble clic en Chrome, Edge o Firefox.
- **Online (GitHub Pages):** Visita `https://TU_USUARIO.github.io/gta6-voxel/` una vez desplegado.

## 📋 Registro de cambios (Changelog)
- **Fase 1:** Motor WebGL2 base, geometría cúbica instanciada, sombras PCF, agua procedural y arquitectura inicial de Vice City.
- **Fase 2:** Ciclo completo día/noche con atardecer Vice City, luces puntuales en farolas, semáforos funcionales, tráfico IA y peatones.
- **Fase 3 (Actual):** Personaje Jason basado en diseño de referencia, postprocesado Bloom HDR, sistema de entrada/salida de vehículos con físicas de conducción, combate con armas y motor de sonido procedural Web Audio API.
