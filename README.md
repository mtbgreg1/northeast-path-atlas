# Northeast Path Atlas

An interactive map of protected bike paths (paved and gravel multi-use paths, rail-trails, separated bike lanes and car-free roads) from Maine to Virginia, with an optional layer of dirt and gravel roads and a satellite imagery toggle.

**Live map:** https://mtbgreg1.github.io/northeast-path-atlas/

## Data

- Paths, roads and base map: © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available under the Open Database License (ODbL). Extract dated October 9, 2026.
- A few trails missing from OpenStreetMap are drawn from the USGS National Digital Trails dataset and USDA Forest Service trail data (public domain).
- Land polygons: OpenStreetMap Data (osmdata.openstreetmap.de), ODbL.
- Terrain shading: Mapzen / AWS Terrain Tiles.
- Satellite imagery: USGS The National Map (public domain), loaded live.
- Map rendering: MapLibre GL JS. Label font: Noto Sans (SIL Open Font License).

The tile data in `data/` is packed into PNG images so the same files also work in hosts that only serve standard web file types.
