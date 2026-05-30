# 🕹️ NEON ARCADE

Una máquina recreativa retro en el navegador. Una sola cabina con pantalla CRT 4:3
desde la que eliges entre 4 juegos, lees las instrucciones y juegas — todos comparten
el mismo tamaño de pantalla.

## Juegos

| Juego | Tipo | Archivo |
|-------|------|---------|
| 🟡 **Neon Chomp** | Laberinto / comecocos | `pacman.html` |
| 🧱 **Neon Tetris** | Puzzle de bloques | `tetris.html` |
| 🦍 **Barrel Climb** | Plataformas / trepar | `donkey-kong.html` |
| 🏎️ **Apex GP** | Carreras F1 | `f1.html` |

## Controles de la cabina

- **◄ ►** — cambiar de juego
- **ENTER** — confirmar / empezar
- **ESC** o botón **✕ MENÚ** — salir del juego y volver al selector

Cada juego muestra sus propios controles en la pantalla de instrucciones.

## Cómo se publica (GitHub Pages)

El sitio es 100% estático (HTML + JS, sin build). Solo hay que servir la carpeta.
La página de inicio es `index.html`.

1. Sube los archivos a un repositorio de GitHub.
2. En el repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Elige la rama (`main`) y la carpeta `/ (root)`.
4. En unos minutos estará en `https://<usuario>.github.io/<repo>/`.

## Local

```bash
npx http-server -p 8765
# abre http://127.0.0.1:8765
```
