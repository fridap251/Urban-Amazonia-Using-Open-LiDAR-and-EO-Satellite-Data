📦 amazonian-discovery-2025/
├── 📁 data/
│   ├── lidar/                # Clipped LAZ/LAS or Entwine EPT references
│   ├── satellite/            # Amazonia-1 WFI COGs / thumbnails
│   ├── historical_maps/      # Georeferenced TIFFs / shapefiles
│   └── geojson/              # Final annotated sites, bounding boxes
│
├── 📁 notebooks/
│   ├── 01_lidar_preprocessing.ipynb         # PDAL + Entwine extraction
│   ├── 02_ndvi_amazonia1.ipynb              # NDVI vegetation anomaly detection
│   ├── 03_overlay_historic_maps.ipynb       # Raster alignment + overlay
│   ├── 04_clustering_rooftop_patterns.ipynb # ML-based structure detection
│   └── 05_visualization_export.ipynb        # GeoTIFFs, hillshades, RGB composites
│
├── 📁 scripts/
│   ├── fetch_stac_scenes.py     # Python script to query STAC and download assets
│   ├── run_ndvi_stack.sh        # Bash script using GDAL or rio stack
│   └── convert_ept_to_laz.py    # If working with EPT, localize subset tiles
│
├── 📁 outputs/
│   ├── ndvi_exports/
│   ├── lidar_dsm_dtm/
│   └── final_maps/              # PNGs, QGIS project, Cesium-ready tiles
│
├── 📁 presentation/
│   ├── deck.pdf / deck.key      # Pitch deck or visual storytelling
│   └── flythrough.mp4           # Video animation (Blender/Cesium)
│
├── 📄 environment.yml           # Conda or pipenv environment
├── 📄 LICENSE                   # MIT or GPL-3.0
├── 📄 README.md                 # Overview, team, data links
└── 📄 submission.md             # Cleaned version of write-up
