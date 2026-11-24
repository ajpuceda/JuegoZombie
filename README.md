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
| `Clic izq.` | **Disparar** (mantén para automáticas) |
| `Espacio` | **Saltar** (mantén = saltos encadenados) |
| `E` | Entrar a tiendas / comprar / **entrar-salir del coche** |
| `W / S` (en coche) | **Acelerar / frenar** — el ratón gira el volante |
| `1 - 4` | Armas: Pistola (∞) · SMG · Fusil · Escopeta |
| `ESC` | Pausa (clic para volver) |
| `P` | Pausa / reanudar |
| `M` | Sonido on/off |
| `H` | Mostrar/ocultar ayuda |

## 🌆 Características

- **👮 ¡Policía que se defiende!** — ataca a los civiles (o a un policía) y sube tu nivel de búsqueda ★★★: uniformados azules aparecen, **te persiguen y te pegan**. Pásate 40 s sin líos y sin policía viva, y te pierden de vista (estilo GTA)
- **🚗 Coches robables y destructibles** — 18 coches aparcados: `E` para entrar, `W/S` para conducir y **atropella a la gente** para ganar dinero. ¡Dispara a los coches y explotan con bola de fuego, humo y onda expansiva (reacción en cadena incluida!)
- **🚶 Peatones por las calles** — la ciudad está viva: la gente pasea por las aceras, huye en pánico al oír disparos y suelta dinero si... bueno, estilo GTA clásico
- **👤 Enemigos humanos** — oleadas de pandilleros (caminante, corredor y bruto) con ropa, gorras y piel humana
- **Partida guardada automáticamente** — la oleada, el dinero, las armas y la posición se conservan al recargar la página (botón *CONTINUAR*); morir borra la partida
- **Enemigos cada vez más rápidos** — cada oleada +7% de velocidad y +8 de vida (hasta +80%)
- **Cámara en primera persona** con arma visible y balanceo al andar (V = cambiar a 3ª persona)
- **Salto con Espacio** — física de gravedad, saltos encadenados estilo Minecraft
- **Gráficos detallados**: edificios con ventanas y puertas, árboles volumétricos, pájaros, hojas que caen y **nubes a la deriva**
- Ciudad 3D grande: calles, edificios, parques y dos tiendas a las que puedes entrar
- 4 armas, armería y farmacia (botiquines y chaleco)
- Minimapa (¡con los coches marcados!), HUD retro con nivel de búsqueda, efectos de partículas y sonido chiptune suave

## 🛠️ Tecnología

WebGL crudo con sombreadores propios, matemática de matrices escrita a mano y motor de juego completo (IA de enemigos con evasión de obstáculos, peatones con paseo y pánico, sistema de búsqueda con policía que responde a los ataques, raycast de balas contra enemigos/peatones/coches, explosiones con reacción en cadena, colisiones AABB, física de conducción, guardado en localStorage) en ~1600 líneas de JavaScript sin ningún framework.

---

Hecho con ❤️ por **Antonio Pena Uceda** · creado con [Vibe](https://chat.mistral.ai)
