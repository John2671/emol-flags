# 🌎 Flag Challenge

Un juego diario de adivinar banderas del mundo, directo en el navegador: sin instalación y con un solo archivo HTML.

**🎮 Jugar ahora:** [john2671.github.io/emol-flags](https://john2671.github.io/emol-flags/)

---

## Cómo se juega

Cada día hay un **desafío nuevo de 30 países**, el mismo para todos los jugadores. El juego te muestra el nombre de un país y tienes que encontrar su bandera entre las de la grilla. Las que vas resolviendo quedan marcadas con su nombre, así te las vas aprendiendo.

- ✅ **Aciertas** → la bandera queda revelada con su nombre.
- ❌ **Fallas** → cuenta como error, te muestra la bandera correcta en gris y pasas a la siguiente. Solo hay un intento por bandera.
- 📍 **Mostrar ubicación** → activa un mapa real (OpenStreetMap) que hace zoom al país que acabas de resolver.
- 🎲 **Modo aleatorio** → si quieres seguir jugando, puedes pasar a un set al azar cuando quieras.

Cada bandera se juega una sola vez, así que el resultado final siempre suma 30: por ejemplo, 27 aciertos y 3 errores.

## Estadísticas

- **Personales:** tus días jugados, tu racha de días, tu mejor día y las banderas que más te cuestan.
- **Globales:** cómo le fue a todos los jugadores hoy y cuáles son las banderas más difíciles.
- **Compartir:** al terminar el desafío del día puedes copiar tu resultado para compartirlo.

## Características

- 195 países con sus banderas (vía [flagcdn.com](https://flagcdn.com))
- Desafío diario igual para todos, que se guarda aunque recargues la página
- Mapa interactivo con zoom automático por país, usando **Leaflet** y mapas de **OpenStreetMap**
- Marcador simple: aciertos y errores
- 100% responsive: funciona bien en el celular
- Sin frameworks ni build: es un solo archivo `.html`

## Tecnologías

- HTML, CSS y JavaScript vanilla
- [Leaflet.js](https://leafletjs.com/) para el mapa interactivo
- Mapas de [OpenStreetMap](https://www.openstreetmap.org/) (contribuidores de OSM)
- Banderas servidas por [flagcdn.com](https://flagcdn.com)
- [Supabase](https://supabase.com/) para las estadísticas globales

## Correrlo localmente

No necesitas nada especial, es un archivo estático:

```bash
git clone https://github.com/john2671/emol-flags.git
cd emol-flags
# abre index.html directo en el navegador, o sirve la carpeta con:
python3 -m http.server 8000
```

Y entra a `http://localhost:8000`.

## Créditos

- Datos y mapas: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors
- Banderas: [flagcdn.com](https://flagcdn.com)

## Licencia

MIT: úsalo, modifícalo y compártelo libremente.
