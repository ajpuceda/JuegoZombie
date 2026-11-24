# Zombie City 3D 🧟🎮

Juego estilo GTA, hecho **100% en WebGL puro** — un solo archivo HTML, sin librerías ni dependencias.

## 🕹️ Cómo jugar

**Opción 1 (local):** descarga `index.html` y ábrelo con doble clic en cualquier navegador.

**Opción 2 (online):** juega directo en `https://ajpuceda.github.io/JuegoZombie/`.

## 🔐 Cuentas: tu partida es SOLO tuya

Pantalla de inicio con **login y contraseña** (`ENTRAR / CREAR CUENTA`): cada usuario tiene su **propia partida guardada y su propia ciudad** (semilla única por cuenta). O entra como `INVITADO` para la partida local clásica. Las contraseñas se guardan solo como hash (SHA-256).

## ⌨️ Controles

| Tecla | Función |
|---|---|
| `W A S D` | Moverse (también flechas) |
| `Ratón (solo mover)` | **Girar cámara — estilo Minecraft, sin clics** |
| `V` | **Cámara 1ª / 3ª persona** |
| `Shift` | Correr |
| `Clic izq.` | **Disparar** — también **desde el coche** |
| `Espacio` | **Saltar** |
| `E` | Entrar a **edificios** y tiendas / comprar / entrar-salir del coche |
| `W / S` (en coche) | Acelerar / frenar |
| `1 - 4` | Armas: Pistola (∞) · SMG · Fusil · Escopeta |
| `P` / `ESC` | Pausa |
| `M` | Sonido on/off · `H` ayuda |

## 🌆 Características

- **🏙️ Bloques-wieżowce (rascacielos)** — al lado de los bloques pequeños hay **torres de pisos** azules de hasta 36 m con todas las ventanas
- **🏢 VARIOS pisos dentro de cada edificio** — escaleras en zigzag con barandillas y lámparas en cada planta: baja y sube por todas (¡los rascacielos tienen hasta 6!)
- **👮 La POLICÍA entra detrás de ti a los edificios** — te persigue escaleras arriba, y si te escondes en un piso superior, **te dispara desde abajo**
- **🎯 La policía no dispara de inmediato** — primero apunta: se ve el **"!" rojo** sobre su cabeza, y el **fogonazo** al disparar. Uniforme azul marino + gorra blanca + chaleco reflectante amarillo: los reconoces de lejos
- **🚗 Conduce y dispara a la vez** — dentro del coche puedes disparar con clic; la policía puede volar tu coche
- **🚶 Peatones que esquivan autos** — huyen de los disparos y saltan a un lado si intentas atropellarlos
- **👁️ Personajes con ojos**, coches destructibles con explosiones en cadena, ★★★ nivel de búsqueda GTA, oleadas de pandilleros, guardado automático por cuenta, armería y farmacia
- Minimapa (¡coches y policía marcados!), HUD retro, partículas y sonido chiptune suave

## 🛠️ Tecnología

WebGL crudo, matrices a mano, motor de juego completo (IA con evasión, policía que persigue y dispara dentro y fuera de los edificios, interiores multiplanta generados proceduralmente, cuentas con hash SHA-256 + semilla de ciudad por usuario, física de conducción, explosiones en cadena) en un único archivo HTML sin frameworks.

---

Hecho con ❤️ por **Antonio Pena Uceda** · creado con [Vibe](https://chat.mistral.ai)
