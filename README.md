# Safe School Paths for Kids in Copenhagen

This project analyses cycling accessibility to schools in Copenhagen, with a focus on safe routes for children.

The project uses geospatial data, OpenStreetMap data, and network analysis to compare:

- shortest routes to school
- safest routes to school
- spatial differences in accessibility across school districts

## Project structure

```text
safe-school-paths-cph/
├── notebooks/
├── data/
│   ├── raw/
│   └── processed/
├── README.md
```

## Notebooks

Run the notebooks in the following order:

1. `00_download_osm.ipynb`
2. `01_prepare_datasets.ipynb`
3. `03_prepare_network.ipynb`
4. `04_route_accessibility.ipynb`
5. `05_route_compute.ipynb`
6. `06_accessibility_analysis.ipynb`

### Optional

Running the following notebooks are optional:

7. `02_voronoi_school_allocation_visualisation.ipynb`

---

## Data

All datasets used in the project are included in the repository.

- `data/raw/` contains original datasets from Copenhagen Municipality
- `data/processed/` contains processed layers and final results

---

## Main tools

The project uses:

- Python
- Jupyter Notebook
- GeoPandas
- OSMnx
- NetworkX
- Pandas
- Matplotlib

---

## Author

Peter Kriegel  
IT University of Copenhagen
