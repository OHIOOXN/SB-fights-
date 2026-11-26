# SB-fights-
fight with sb characters

Juego 1v1 local (hot-seat) en un solo `index.html`, sin dependencias.

## Cómo jugar

1. **Draft:** ambos jugadores preparan **5 copias de diamond** (la única plantilla actual). Clic en la carta para añadir una copia; **Quitar una copia** o **Limpiar selección** para corregir.
2. **Batalla:** tablero de 9×8. Cada `diamond` tiene:
   - ❤️ 10 corazones
   - ↦ movimiento de 1-2 casillas en cualquier dirección (incluye diagonales)
   - ⚔️ daño 4
   - ✨ habilidad disponible cada 2 turnos
3. En tu turno seleccionas **uno** de tus 5 `diamond` y puedes:
   - moverlo 1 o 2 casillas en cualquier dirección (sin atravesar ni ocupar casillas con personajes),
   - atacar a un enemigo adyacente (también en diagonal) por 4 corazones, o
   - usar su habilidad: 4 corazones a **cualquier** enemigo del tablero, sin importar la distancia.
4. Si al mover terminas junto a un enemigo, ese enemigo queda marcado y puedes clickarlo para atacar. También puedes atacar sin moverte si ya eras adyacente.
5. Usar la habilidad consume el turno. Tras usarla pasan 2 de tus turnos hasta que vuelve a estar lista: la usas en tu turno N y puedes volver a usarla en el N+2. Mientras tanto el botón muestra `Habilidad (2 turnos)` o `Habilidad (1 turno)`.
6. Gana quien deja al otro sin personajes.

Botones: **Habilidad** (activa/cancela la habilidad), **Terminar turno**, **Revancha** (mismos personajes) y **Cambiar personajes** (nuevo draft).

## Personajes

| Personaje | Vida | Movimiento | Ataque | Habilidad |
|---|---:|---|---:|---|
| diamond 💎 | 10 | 1-2 casillas, cualquier dirección | 4 | 4 de daño a cualquier enemigo, cada 2 turnos |

## Abrir

Abre `index.html` en el navegador. No necesita servidor ni instalación.

## Publicar

El nombre del repositorio en GitHub es `SB-fights-`. El título del juego es `SB-fights-`.

```bash
git remote add origin git@github.com:OHIOOXN/SB-fights-.git
git push -u origin main
```

Luego publica la rama `main` en GitHub Pages desde Settings → Pages.
