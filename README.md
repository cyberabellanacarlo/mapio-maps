# mapio-maps

Offline map packs for the Mapio app. Map data © OpenStreetMap contributors (ODbL).

## Contents
- One `.mpk` pack (zip) per Philippine city/municipality, containing vector tiles (z13–15, PMTiles), a routing graph, POIs and places.
- Packs are published as GitHub Release assets, grouped by island group/region:
  `packs-luzon-north`, `packs-luzon-south`, `packs-visayas`, `packs-mindanao`.
- Manifest (with sha256, size and download `url` for every pack):
  https://github.com/cyberabellanacarlo/mapio-maps/releases/download/manifest/manifest.json

## Attribution & license
- Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available under the
  [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/). The packs are a derived database
  of OpenStreetMap data and are likewise made available under the ODbL.
- OSM extract via [Geofabrik](https://download.geofabrik.de/) (philippines-latest.osm.pbf).
- Vector tiles built with the [Protomaps](https://protomaps.com) basemap schema. Attribution: "Protomaps © OpenStreetMap".
