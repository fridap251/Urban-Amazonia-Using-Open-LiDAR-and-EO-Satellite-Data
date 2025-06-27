# Unearthing Rooftop Agroheritage and Sacred Layouts in Urban Amazonia

This project combines open-access LiDAR and Earth Observation (EO) satellite data to uncover archaeological and cultural structures hidden beneath São Paulo’s urban canopy. Using high-resolution LiDAR from Prefeitura Municipal de São Paulo (PMSP) and daily Amazonia-1 WFI imagery, we discovered rooftop agriculture zones, geometric alignments, and remnants of sacred Afro-Brazilian spatial logic—validated through STAC catalogs, historical maps, and oral archives.

---

## 🌍 Objectives

- Detect rooftop agriculture and microterraces in informal settlements
- Identify alignment patterns consistent with sacred/ceremonial layouts
- Cross-validate with Amazonia-1 vegetation anomalies
- Package findings for reproducible analysis and open visualization

---

## 📦 Data Sources

| Dataset | Type | Source |
|--------|------|--------|
| **PMSP LiDAR** | 1m LiDAR (Entwine + LAZ) | `s3://ept-m3dc-pmsp` |
| **Amazonia-1 Satellite** | WFI imagery (60m, COG) | [STAC API](https://stac.scitekno.com.br/v100) |
| **Historical Maps** | Raster/Vector overlays | Arquivo Histórico de São Paulo |
| **Oral Knowledge** | Local records | Projeto Quilombola Vargem Grande |

---

## 📁 Project Structure

# Unearthing Rooftop Agroheritage and Sacred Layouts in Urban Amazonia

This project combines open-access LiDAR and Earth Observation (EO) satellite data to uncover archaeological and cultural structures hidden beneath São Paulo’s urban canopy. Using high-resolution LiDAR from Prefeitura Municipal de São Paulo (PMSP) and daily Amazonia-1 WFI imagery, we discovered rooftop agriculture zones, geometric alignments, and remnants of sacred Afro-Brazilian spatial logic—validated through STAC catalogs, historical maps, and oral archives.

---

## 🌍 Objectives

- Detect rooftop agriculture and microterraces in informal settlements
- Identify alignment patterns consistent with sacred/ceremonial layouts
- Cross-validate with Amazonia-1 vegetation anomalies
- Package findings for reproducible analysis and open visualization

---

## 📦 Data Sources

| Dataset | Type | Source |
|--------|------|--------|
| **PMSP LiDAR** | 1m LiDAR (Entwine + LAZ) | `s3://ept-m3dc-pmsp` |
| **Amazonia-1 Satellite** | WFI imagery (60m, COG) | [STAC API](https://stac.scitekno.com.br/v100) |
| **Historical Maps** | Raster/Vector overlays | Arquivo Histórico de São Paulo |
| **Oral Knowledge** | Local records | Projeto Quilombola Vargem Grande |

---

## 📁 Project Structure

amazonian-discovery-2025/
├── data/ # Source LAZ, COGs, GeoJSONs
├── notebooks/ # Jupyter analysis steps
├── scripts/ # STAC fetchers, PDAL configs
├── outputs/ # Final maps, tiles, videos
├── presentation/ # Slides, animations, video
├── environment.yml # Conda environment for full repro
├── README.md
├── submission.md

yaml
Copy
Edit

---

## 🛰️ Tools Used

- [PDAL](https://pdal.io/) – LiDAR processing
- [STAC tools](https://stacspec.org/) – EO catalog querying
- [GDAL / rasterio](https://rasterio.readthedocs.io/) – NDVI + geospatial transforms
- [QGIS](https://qgis.org/) – Final cartography
- [Blender](https://www.blender.org/) – 3D LiDAR flythrough
- [CesiumJS](https://cesium.com/platform/cesiumjs/) – Interactive viewer (optional)

---

## 📊 Key Discoveries

- 📍 Rooftop agricultural zones (centroid: `-23.5897, -46.6791`)
- 🌀 Alignment with precolonial spatial layouts
- 📈 Vegetation growth confirmed via 90-day NDVI time series

---

## 🧪 Reproducibility

Clone this repo, activate the Conda environment, and run:

```bash
jupyter lab

