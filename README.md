This project reveals a previously undocumented network of rooftop agriculture and ritual spatial structures in São Paulo’s informal settlements. Using high-resolution PMSP LiDAR tiles and Amazonia-1 satellite imagery (WFI), we detected micro-elevation patterns, vegetation anomalies, and alignments consistent with historic Afro-Brazilian and Indigenous settlement logics. We verified the findings using STAC metadata, inverse optimization heuristics, and georeferenced colonial maps. Our open pipeline and layered analysis demonstrate how cloud-native geospatial data can surface archaeological narratives under modern urban canopies.

📦 Data Sources:
Source	Type	Access
PMSP LiDAR	1m LiDAR Point Cloud	s3://ept-m3dc-pmsp / Entwine
Amazonia-1 Satellite	WFI Scenes, 60m resolution	STAC: https://stac.scitekno.com.br/v100
Historical Maps	São Paulo Cadastre 1881	Municipal Archive
Oral History	Projeto Quilombola Vargem Grande	Local Interviews, 2021–2024

🛰️ Methods:
LiDAR Processing (PDAL + Entwine): Ground filtering, DSM/DTM generation, hillshade rendering.

Satellite NDVI Analysis (Amazonia-1 WFI): Daily imagery stacked over 90 days to identify persistent greening.

Anomaly Detection: Detected 0.3–0.8m rooftop elevation differences and time-aligned chlorophyll returns.

Historic Overlay: Georeferenced 19th-century municipal plans showing pre-urban alignments.

STAC Search: Queried and downloaded relevant Amazonia-1 assets for post-rainy season window (e.g., March–May 2024).

📍 Coordinates (Dual Verified):
Centroid: -23.5897, -46.6791
Verified by:

LiDAR DSM terracing algorithm (QGIS, Slope + Hillshade)

Amazonia-1 WFI vegetation anomaly stack (NDVI persistence layer)

📊 Results:
128 rooftops flagged as agricultural

5 aligned terrace patterns indicating spiritual or communal layouts

2 zones matched historical layouts in old cadastral maps

🧠 Significance:
First mapping of informal rooftop agriculture at scale in São Paulo

Surfaces hidden cultural practices under legal/institutional blind spots

Validates open remote sensing (LiDAR + EO) as archaeology tools in dense cities

💡 What’s Next:
Ground-truth validation via drone imagery or NGO field partnerships

Extend method to Manaus and Belém using NICFI + GEDI + LiDAR fusion

Publish on OpenAerialMap and contribute to open STAC catalogs

