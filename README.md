# 🌎 Flag Challenge

Un juego de adivinar banderas del mundo, directo en el navegador — sin instalación, sin backend, un solo archivo HTML.

**🎮 Jugar ahora:** [tu-usuario.github.io/flag-challenge](#) *(actualizá este link una vez que actives GitHub Pages)*

---

## Cómo se juega

En cada ronda aparecen **30 países al azar** de los 195 posibles. El juego te muestra el nombre de un país y tenés que encontrar su bandera correcta entre las que se ven en la grilla. Las que vas acertando quedan marcadas y visibles, así de paso te las vas aprendiendo.

- ✅ **Acertaste** → la bandera queda revelada con su nombre, sumás puntos y racha.
- ❌ **Te equivocaste** → la bandera tiembla y perdés algo de puntaje (podés elegir si te muestra o no el nombre correcto al fallar).
- 🏳️ **¿No tenés idea?** → apretá **"Me rindo"** y te muestra la respuesta y su ubicación en el mapa.
- 📍 **Mostrar ubicación al acertar** → activa un mapa real (OpenStreetMap) que hace zoom al país que acabás de adivinar.

El puntaje premia las rachas: mientras más seguidas aciertes, más vale cada acierto.

## Características

- 195 países con sus banderas (vía [flagcdn.com](https://flagcdn.com))
- Mapa interactivo real con zoom automático por país, usando **Leaflet** + tiles de **OpenStreetMap**
- Sistema de racha y puntaje
- Botón de "rendirse" que revela la respuesta sin cortar la partida
- 100% responsive (anda bien en el celular)
- Sin frameworks, sin build, sin dependencias que instalar — es un solo archivo `.html`

## Tecnologías

- HTML / CSS / JavaScript vanilla
- [Leaflet.js](https://leafletjs.com/) para el mapa interactivo
- Tiles de [OpenStreetMap](https://www.openstreetmap.org/) (contribuidores de OSM)
- Banderas servidas por [flagcdn.com](https://flagcdn.com)

## Correrlo localmente

No hace falta nada especial, es un archivo estático:

```bash
git clone https://github.com/tu-usuario/flag-challenge.git
cd flag-challenge
# abrí index.html directo en el navegador, o serví la carpeta con:
python3 -m http.server 8000
```

Y entrá a `http://localhost:8000`.

## Créditos

- Datos y tiles del mapa: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors
- Banderas: [flagcdn.com](https://flagcdn.com)

## Licencia

MIT — usalo, modificalo, compartilo libremente.
