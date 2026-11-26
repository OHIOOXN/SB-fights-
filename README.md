# SB-fights-
fight with sb characters

Juego 1v1 local (hot-seat) en un solo `index.html`, sin dependencias.

## Cómo jugar

1. **Draft:** ambos jugadores preparan **5 copias de diamond** (la única plantilla actual). Clic en la carta para añadir una copia; **Quitar una copia** o **Limpiar selección** para corregir.
2. **Batalla:** tablero de **16×16**. Cada `diamond` tiene:
   - ❤️ **100** de vida (mostrada como barra)
   - ♛ movimiento de **reina de ajedrez, hasta 3 casillas**
   - ⚔️ **40** de daño
   - 💥 **knockback de 4 casillas** al golpear
   - ✨ habilidad disponible **cada 2 turnos**
3. En tu turno seleccionas **uno** de tus 5 `diamond` y puedes:
   - moverlo como una reina hasta 3 casillas en horizontal, vertical o diagonal (sin atravesar ni ocupar casillas con personajes),
   - atacar a un enemigo adyacente (también en diagonal) por 40 de daño y empujarlo 4 casillas, o
   - activar su habilidad.
4. **Knockback:** tras recibir un golpe, el objetivo es empujado 4 casillas en dirección contraria al atacante. El empuje se detiene antes si llega al borde del tablero o encuentra otro personaje. Un objetivo invencible no recibe daño ni empuje.
5. **Habilidad:** al activarla el personaje queda **invencible entre 1 y 2 turnos** y **no puede moverse** (sí puede atacar). El botón pasa a «Salir de habilidad» a partir de tu turno siguiente: puedes pulsarlo para terminar tras 1 turno y moverte ese mismo turno. Si no lo pulsas, la habilidad termina automáticamente al acabar tu segundo turno. Desde que sales, debes esperar **2 de tus turnos** para volver a usarla; mientras tanto el botón muestra `Habilidad (2 turnos)` o `Habilidad (1 turno)`.
6. **Barra de vida:** verde por encima del 50 %, amarilla entre 25 % y 50 %, roja por debajo del 25 %. Pasa el cursor sobre un personaje para ver sus PV exactos.
7. Gana quien deja al otro sin personajes.

Botones: **Activar habilidad** / **Salir de habilidad**, **Terminar turno**, **Revancha** (mismos personajes) y **Cambiar personajes** (nuevo draft).

## Personajes

| Personaje | Vida | Movimiento | Ataque | Knockback | Habilidad |
|---|---:|---|---:|---:|---|
| diamond 💎 | 100 | Reina, 3 casillas | 40 | 4 casillas | Invencible 1-2 turnos sin moverte, cada 2 turnos |

## Abrir

Abre `index.html` en el navegador. No necesita servidor ni instalación.

## Publicar

El nombre del repositorio en GitHub es `SB-fights-`. El título del juego es `SB-fights-`.

```bash
git remote add origin git@github.com:OHIOOXN/SB-fights-.git
git push -u origin main
```

Luego publica la rama `main` en GitHub Pages desde Settings → Pages.
