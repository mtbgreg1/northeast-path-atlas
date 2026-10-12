# Northeast Path Atlas

An interactive map of protected bike paths (paved and gravel multi-use paths, rail-trails, separated bike lanes and car-free roads) from Maine to Virginia and west through Ohio (all of New England, New York, New Jersey, Pennsylvania, Delaware, Maryland, DC, Virginia, West Virginia and Ohio), with an optional layer of dirt and gravel roads and a satellite imagery toggle.

Narrow singletrack is kept off the main map: trails that OpenStreetMap tags as mountain-bike trails, that wind like singletrack, or that are unpaved hiking paths with nothing marking them as built bike paths are shown only in the optional **Other trails** layer (dotted for likely singletrack), and clicking one says why it was left off. Former railways, canal towpaths and carriage roads are never filtered.

**Live map:** https://mtbgreg1.github.io/northeast-path-atlas/

## Data

- Paths, roads and base map: © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available under the Open Database License (ODbL). Extract dated October 9, 2026.
- A few trails missing from OpenStreetMap are drawn from the USGS National Digital Trails dataset and USDA Forest Service trail data (public domain).
- Land polygons: OpenStreetMap Data (osmdata.openstreetmap.de), ODbL.
- Terrain shading: Mapzen / AWS Terrain Tiles.
- Satellite imagery: USGS The National Map (public domain), loaded live.
- Map rendering: MapLibre GL JS. Label font: Noto Sans (SIL Open Font License).

The tile data in `data/` is packed into PNG images so the same files also work in hosts that only serve standard web file types.
