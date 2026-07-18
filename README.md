# Projects

| Repo | What it is | Stack | Status |
|---|---|---|---|
| [geodetic-pipeline](https://github.com/tarpous/geodetic-pipeline) | GNSS time-series platform: validated ingestion → PostGIS → anomaly detection, benchmarked against published earthquake offsets (Kahramanmaraş 2023) | Python · pandera · PostGIS · ruptures · scikit-learn | ✅ complete |
| [urban-canopy-detection](https://github.com/tarpous/urban-canopy-detection) | Tree-crown detection on aerial imagery: YOLO26 vs RF-DETR vs published RetinaNet baseline on the open NEON benchmark, GeoJSON outputs, live demo | Python · Ultralytics · RF-DETR · SAHI · rasterio | 🚧 building |
| [landcover-sentinel2](https://github.com/tarpous/landcover-sentinel2) | Sentinel-2 land cover: classical Random Forest vs U-Net vs LoRA-fine-tuned geospatial foundation model, with label-efficiency analysis | Python · scikit-learn · PyTorch · TerraTorch | ⏳ queued |

**Currently building:** `urban-canopy-detection` — YOLO26 vs RF-DETR vs a published baseline on the open NEON tree-crown benchmark.
