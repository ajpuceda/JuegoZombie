# Zombie City 3D 🧟🎮

Juego estilo GTA con zombis, hecho **100% en WebGL puro** — un solo archivo HTML, sin librerías ni dependencias.

## 🕹️ Cómo jugar

**Opción 1 (local):** descarga `index.html` y ábrelo con doble clic en cualquier navegador.

**Opción 2 (online):** activa *GitHub Pages*:
1. En este repo: **Settings → Pages**
2. Source: **Deploy from a branch** → rama `main`, carpeta `(root)`
3. En 1-2 minutos estará en `https://ajpuceda.github.io/JuegoZombie/`

## ⌨️ Controles

| Tecla | Función |
|---|---|
| `W A S D` | Moverse (también flechas) |
| `Ratón (solo mover)` | **Girar cámara — estilo Minecraft, sin clics** |
| `V` | **Cámara 1ª / 3ª persona** (por defecto: 1ª persona) |
| `Shift` | Correr |
| `Rueda del ratón` | Zoom (FOV en 1ª persona) |
| `Clic izq.` | **Disparar** (mantén para automáticas) |
| `Espacio` | **Saltar** (mantén = saltos encadenados) |
| `E` | Entrar a tiendas / comprar / **entrar-salir del coche** |
| `W / S` (en coche) | **Acelerar / frenar** — el ratón gira el volante |
| `1 - 4` | Armas: Pistola (∞) · SMG · Fusil · Escopeta |
| `ESC` | Pausa (clic para volver) |
| `P` | Pausa / reanudar |
| `M` | Sonido on/off |
| `H` | Mostrar/ocultar ayuda |

## 🧟 Características

- **🚗 Coches robables** — 18 coches aparcados por la ciudad: pulsa `E` para entrar, `W/S` para conducir y **atropella zombis** para ganar dinero (¡estilo GTA!). Los zombis no te hacen daño dentro del coche
- **Partida guardada automáticamente** — la oleada, el dinero, las armas y la posición se conservan al recargar la página (botón *CONTINUAR*); morir borra la partida
- **Zombis cada vez más rápidos** — cada oleada +7% de velocidad y +8 de vida (hasta +80%), ¡no te confíes!
- **Cámara en primera persona** con arma visible y balanceo al andar (V = cambiar a 3ª persona)
- **Salto con Espacio** — física de gravedad, saltos encadenados estilo Minecraft
- **Gráficos detallados**: edificios con ventanas (¡algunas encendidas!) y puertas, árboles con ramas y copas volumétricas, pájaros que vuelan, hojas que caen y **nubes a la deriva**
- Ciudad 3D grande: calles, edificios, parques y dos tiendas a las que puedes entrar
- Zombis de 3 tipos (caminante, corredor y bruto) en oleadas infinitas
- 4 armas que se compran con el dinero de los zombis eliminados
- Armería (armas y munición) y farmacia (botiquines y chaleco antibalas)
- Minimapa (¡con los coches marcados!), HUD retro, efectos de partículas y sonido chiptune

## 🛠️ Tecnología

WebGL crudo con sombreadores propios, matemática de matrices escrita a mano y motor de juego completo (IA de zombis con evasión de obstáculos, raycast de balas, colisiones AABB, física de conducción, cámara con pointer lock estilo Minecraft, física de salto, guardado en localStorage) en ~1300 líneas de JavaScript sin ningún framework.

---

Hecho con ❤️ por **Antonio Pena Uceda** · creado con [Vibe](https://chat.mistral.ai)
