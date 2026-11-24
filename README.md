# Zombie City 3D 🧟🎮

Juego estilo GTA, hecho **100% en WebGL puro** — un solo archivo HTML, sin librerías ni dependencias.

## 🕹️ Cómo jugar

**Opción 1 (local):** descarga `index.html` y ábrelo con doble clic en cualquier navegador.

**Opción 2 (online):** juega directo en `https://ajpuceda.github.io/JuegoZombie/` (GitHub Pages, rama `main`, carpeta `(root)`).

## ⌨️ Controles

| Tecla | Función |
|---|---|
| `W A S D` | Moverse (también flechas) |
| `Ratón (solo mover)` | **Girar cámara — estilo Minecraft, sin clics** |
| `V` | **Cámara 1ª / 3ª persona** (por defecto: 1ª persona) |
| `Shift` | Correr |
| `Rueda del ratón` | Zoom (FOV en 1ª persona) |
| `Clic izq.` | **Disparar** — también **desde el coche** |
| `Espacio` | **Saltar** (mantén = saltos encadenados) |
| `E` | Entrar a **edificios** y tiendas / comprar / entrar-salir del coche |
| `W / S` (en coche) | **Acelerar / frenar** — el ratón gira el volante |
| `1 - 4` | Armas: Pistola (∞) · SMG · Fusil · Escopeta |
| `ESC` | Pausa (clic para volver) |
| `P` | Pausa / reanudar |
| `M` | Sonido on/off |
| `H` | Mostrar/ocultar ayuda |

## 🌆 Características

- **🏢 ¡Puedes entrar en TODOS los edificios!** — puerta marcada, `E` para entrar. Los edificios altos tienen **escaleras hasta un entresuelo** con vistas a la ciudad (y desde donde disparar 😏)
- **👮 Policía que DISPARA** — uniforme azul brillante y gorra blanca para reconocerlos de lejos. Un poco más rápidos que los civiles, **te disparan a pie y también al coche** (¡pueden volarlo!)
- **🚗 Conduce y dispara a la vez** — dentro del coche puedes disparar con clic (tu coche no recibe tus balas)
- **🚶 Peatones que esquivan autos** — la gente pasea por las aceras, huye de los disparos y **salta a un lado** si intentas atropellarla
- **👁️ Personajes con ojos** — todos los humanoides del juego tienen cara con ojos
- **★★★ Nivel de búsqueda GTA** — ataca civiles o policía y sube el nivel: aparecen más policías. Pásate 40 s sin líos y te pierden
- **🚗 Coches robables y destructibles** — 18 coches aparcados: `E` para entrar, `W/S` para conducir. Dispara a los coches y explotan con bola de fuego, humo y reacción en cadena
- **👤 Enemigos humanos** — oleadas de pandilleros (caminante, corredor y bruto), cada oleada +7% velocidad y +8 vida (hasta +80%)
- **Partida guardada automáticamente** — oleada, dinero, armas y posición se conservan al recargar (botón *CONTINUAR*); morir borra la partida
- **Cámara en primera persona** con arma visible y balanceo al andar (V = 3ª persona)
- **Gráficos detallados**: ventanas y puertas, árboles volumétricos, pájaros, hojas que caen, **nubes a la deriva**
- 4 armas, armería y farmacia (botiquines y chaleco)
- Minimapa (¡coches y policía marcados!), HUD retro con nivel de búsqueda, partículas y sonido chiptune suave

## 🛠️ Tecnología

WebGL crudo con sombreadores propios, matrices a mano y motor completo: IA con evasión de obstáculos, policía que persigue y dispara (a pie y a coches), peatones con paseo, pánico y esquiva, interiores generados por edificio con escaleras físicas, raycast de balas contra enemigos/peatones/coches, explosiones en cadena, AABB, física de conducción, guardado en localStorage — en un único archivo HTML sin frameworks.

---

Hecho con ❤️ por **Antonio Pena Uceda** · creado con [Vibe](https://chat.mistral.ai)
