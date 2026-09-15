# 🌎 Flag Master

Un juego de adivinar banderas del mundo, directo en el navegador

**🎮 Jugar ahora:** [https://john2671.github.io/emol-flags/]

---

## Cómo se juega

En cada ronda aparecen **30 países al azar** de los 195 posibles. El juego te muestra el nombre de un país y tienes que encontrar su bandera correcta entre las que se ven en la grilla. Las que vas acertando quedan marcadas y visibles, para facilitar su aprendizaje.

- ✅ **Acertaste** → la bandera queda revelada con su nombre, sumas puntos y racha.
- ❌ **Te equivocaste** → la bandera tiembla y pierdes algo de puntaje (puedes elegir si te muestra o no el nombre correcto al fallar).
- 🏳️ **no sabes?** → click en **"Me rindo"** y te muestra la respuesta y su ubicación en el mapa.
- 📍 **Mostrar ubicación al acertar** → activa un mapa real que hace zoom al país que acabas de adivinar.

El puntaje premia las rachas: mientras más seguidas aciertes, más vale cada acierto.

## Características

- 195 países con sus banderas (vía [flagcdn.com](https://flagcdn.com))
- Mapa interactivo real con zoom automático por país, usando **Leaflet** + tiles de **OpenStreetMap**
- Sistema de racha y puntaje
- Botón de "rendirse" que revela la respuesta sin cortar la partida
- 100% responsive

## Tecnologías

- HTML / CSS / JavaScript vanilla
- [Leaflet.js](https://leafletjs.com/) para el mapa interactivo
- Tiles de [OpenStreetMap](https://www.openstreetmap.org/) (contribuidores de OSM)
- Banderas servidas por [flagcdn.com](https://flagcdn.com)

## Correrlo localmente

No hace falta nada especial, es un archivo estático:

```bash
git clone https://github.com/tu-usuario/flag-master.git
cd flag-master
# abrí index.html directo en el navegador, o serví la carpeta con:
python3 -m http.server 8000
```

Y entrar a `http://localhost:8000`.

## Créditos

- Datos y tiles del mapa: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors
- Banderas: [flagcdn.com](https://flagcdn.com)
