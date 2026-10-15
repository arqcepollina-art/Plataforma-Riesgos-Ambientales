# GeoRiesgo Guatemala

Plataforma de tamizaje de amenazas naturales por polígono de proyecto. Cargue un KMZ, KML, GeoJSON o coordenadas (GTM, WGS84, UTM), visualice el polígono sobre los mapas de amenaza y de contexto, y descargue una ficha PDF con el nivel de exposición.

## Capas

**Amenazas (suman a la exposición global, cuadrícula de 100 m y seis niveles):**

- Inundaciones, deslizamientos y sequía: UIE-URL (2023), vía el Sistema de Información Estratégica (SIE).
- Heladas: UIE-URL (2024).
- Descenso de agua subterránea: Instituto Biosfera, solo Región Metropolitana.
- Sismo: AGIES NSE 2-2018, índice de sismicidad (Io) por municipio, publicado por IDEG/SEGEPLAN.
- Viento: AGIES NSE 2, velocidad básica de viento de diseño por municipio, publicado por IDEG/SEGEPLAN.
- Amenaza volcánica: proximidad a volcanes (UIE-URL / IARNA, 2020).

**Contexto territorial y normativo (no suma a la exposición):**

- Población: WorldPop 2020 (100 m), CC BY 4.0.
- Población indígena por municipio: INE, Censo 2018 (Cuadro A5.2), CC BY.
- Áreas protegidas: SIGAP 2019 (IARNA-URL con base en CONAP), vía SIE.
- Cuencas y subcuencas: HydroBASINS v1c, niveles 6 y 8, con su vertiente.
- Red vial principal: © colaboradores de OpenStreetMap (ODbL), extracto HOT de mayo de 2026.

Las capas nuevas se cargan desde la carpeta `data/`. El sitio debe abrirse desde GitHub Pages o desde un servidor web; abierto como archivo local, el navegador bloquea esas capas.

Herramienta de tamizaje; no sustituye estudios técnicos específicos ni evaluaciones oficiales de CONRED, INSIVUMEH, CONAP o MARN. Antes de un uso comercial, obtener autorización escrita de uso de las capas del SIE (URL) y de AGIES.

Consultoría y Arquitectura Ambiental, S.A.
