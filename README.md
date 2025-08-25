# Tutorial: Map & Validate Pedestrian Flow Estimates (City of Sydney)

Map **precomputed** sidewalk link flows and validate them against City of Sydney pedestrian counters — Colab-ready with sample data.

**Open in Colab:** https://colab.research.google.com/github/meeadsaberi/pedestrian-flows-tutorial/blob/main/Tutorial.ipynb  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/meeadsaberi/pedestrian-flows-tutorial/blob/main/Tutorial.ipynb)

## What this notebook does
- Loads estimated link-level pedestrian flows from a CSV.
- Renders a legible city-scale map (Folium).
- Validates against selected City of Sydney counter sites (nearest-link matching, simple error metrics).
- Does **not** build an OD matrix or estimate a route-choice model.

## Quick start (Colab)
1. Click the **Open in Colab** link or badge above.
2. Run the first install cell (only needed on first run).
3. The sample CSV lets it run instantly; switch to your full dataset later.

## Files
- `Tutorial.ipynb` — main notebook  
- `sample_link_flows.csv` — small sample dataset for quick runs

## Data
By default, the notebook reads the sample CSV. For full runs, update `flows_csv` in the notebook to a public URL or your own file path.

## Attribution & licences
- Street network: **OpenStreetMap contributors** (ODbL)  
- Pedestrian counts: **City of Sydney Open Data** (see their terms)  

Please cite data sources when sharing results.

## Citation (method & validation)
Lilasathapornkit, T., Nourmohammadi, F., & Saberi, M. (2024). *Understanding Walking Route Choice Preferences and Pedestrian Network Flows: From Individual Trajectories to City-Scale Patterns Using Empirical Data from Sydney*. SSRN. https://ssrn.com/abstract=5164102

## Contact
meead.saberi@unsw.edu.au
