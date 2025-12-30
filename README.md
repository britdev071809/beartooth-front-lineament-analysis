# Beartooth Front Lineament Analysis

A reproducible workflow for identifying and visualizing fault lineaments along the Beartooth Front, south-central Montana.

## Project Overview
This repository contains a complete, version‑controlled geospatial analysis project designed to identify and map potential fault lineaments in the Beartooth Front region. The workflow integrates digital elevation model (DEM) processing, analytical hillshading, lineament digitization, GIS compilation, and visualization.

**Author**: Geologist specializing in fault‑lineament analysis and remote sensing.

**Task Link**: [Reproducible Fault Lineament Analysis Workflow for the Beartooth Front, Montana](https://github.com/britdev071809/beartooth-front-lineament-analysis) (this repository)

## Repository Structure
- `data/` – Documentation of data sources and metadata.
- `scripts/` – Python scripts for DEM processing and hillshade generation.
- `docs/` – Methodological protocols and final report.
- `output/` – Final maps and visualizations.

## Workflow Steps
1. **Data Acquisition** – Identify and document publicly available DEM datasets.
2. **DEM Pre‑processing & Hillshade Generation** – Create multiple analytical hillshades to enhance linear features.
3. **Lineament Digitization Protocol** – Define criteria for manual or semi‑automated lineament mapping.
4. **GIS Compilation & Visualization** – Combine hillshades and lineaments into a final map.
5. **Final Report & Release** – Summarize methodology, results, and tectonic implications.

## Final Map
![Example Hillshade with Lineaments](output/hillshade_lineaments.png)

## How to Use
1. Clone this repository.
2. Review the `data_sources.md` file for DEM download instructions.
3. Run the hillshade generation script (`scripts/generate_hillshades.py`).
4. Follow the digitization protocol (`docs/digitization_protocol.md`).
5. Generate your own lineament map using GIS software.
6. Read the final report (`docs/final_report.md`) for interpretation.

## License
This project is shared under the MIT License.