# SB-fights-

Juego 1v1 local (hot-seat) en un solo `index.html`, sin dependencias.

## Cómo jugar

1. **Draft:** el Jugador 1 elige 5 personajes de 10. Luego el Jugador 2 elige 5 de los restantes.
2. **Batalla:** tablero de 9×8. Cada personaje tiene:
   - ❤️ vida
   - ↦ movimiento (casillas por turno, en horizontal/vertical)
   - ⚔️ ataque
3. En tu turno seleccionas **uno** de tus 5 personajes y puedes:
   - moverlo hasta su número de casillas (sin atravesar ni ocupar casillas con personajes), o
   - atacar a un enemigo adyacente.
4. Si al mover terminas junto a un enemigo, ese enemigo queda marcado y puedes clickarlo para atacar. También puedes terminar el turno sin atacar.
5. Gana quien deja al otro sin personajes.

Botones: **Terminar turno**, **Revancha** (mismos personajes) y **Cambiar personajes** (nuevo draft).

## Personajes

| Personaje | Vida | Movimiento | Ataque |
|---|---:|---:|---:|
| Hormiga 🐜 | 3 | 3 | 1 |
| Escarabajo 🪲 | 4 | 2 | 1 |
| Mantis 🦗 | 2 | 4 | 2 |
| Araña 🕷️ | 2 | 3 | 2 |
| Abeja 🐝 | 2 | 4 | 1 |
| Termita 🐛 | 3 | 2 | 2 |
| Cangrejo 🦀 | 4 | 2 | 2 |
| Mariposa 🦋 | 1 | 5 | 1 |
| Escorpión 🦂 | 3 | 3 | 3 |
| Caracol 🐌 | 5 | 1 | 1 |

## Abrir

Abre `index.html` en el navegador. No necesita servidor ni instalación.

## Publicar

El nombre del repositorio en GitHub es `SB-fights-`. El título del juego es `SB-fights-`.

```bash
git remote add origin git@github.com:OHIOOXN/SB-fights-.git
git push -u origin main
```

Luego publica la rama `main` en GitHub Pages desde Settings → Pages.
