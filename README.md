# Tutorial #1: Map & Validate Pedestrian Flow Estimates (City of Sydney)

Map **precomputed** sidewalk link flows and validate them against City of Sydney pedestrian counters — Colab-ready with sample data.

**Open in Colab:** https://colab.research.google.com/github/meeadsaberi/pedestrian-flows-tutorial/blob/main/Tutorial.ipynb  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/meeadsaberi/pedestrian-flows-tutorial/blob/main/Tutorial.ipynb)

## What this notebook does
- Loads estimated link-level pedestrian flows from a CSV.
- Renders a legible city-scale map (Folium).
- Validates against selected City of Sydney counter sites (nearest-link matching, simple error metrics).
- Does **not** build an OD matrix or estimate a route-choice model.

<img width="1195" height="639" alt="Screenshot 2025-08-25 at 10 20 02 am" src="https://github.com/user-attachments/assets/f085b0ff-f9eb-4e7c-b9ab-648bfd9972a6" />

## Quick start (Colab)
1. Click the **Open in Colab** link or badge above.
2. Run the first install cell (only needed on first run).
3. The sample CSV lets it run instantly; switch to your full dataset later.

## Files
- `Tutorial.ipynb` — main notebook  
- `sample_link_flows.csv` — small sample dataset for quick runs

## Data
By default, the notebook reads the sample CSV. For full runs, update `flows_csv` in the notebook to a public URL or your own file path.

<img width="1096" height="353" alt="Screenshot 2025-08-25 at 10 21 41 am" src="https://github.com/user-attachments/assets/a86ce1c4-2b08-4e99-ab5b-64cb2d56d145" />

## Attribution & licences
- Street network: **OpenStreetMap contributors** (ODbL)  
- Pedestrian counts: **City of Sydney Open Data** (see their terms)
- Estimated sidewalk-level pedestrian estimates are shared under the **MIT License**.

Please cite data sources when sharing results.

## Citation (method & validation)
Lilasathapornkit, T., Nourmohammadi, F., & Saberi, M. (2024). *Understanding Walking Route Choice Preferences and Pedestrian Network Flows: From Individual Trajectories to City-Scale Patterns Using Empirical Data from Sydney*. SSRN. https://ssrn.com/abstract=5164102

## Contact
Meead Saberi @UNSW School of Civil and Environmental Engineering (meead.saberi@unsw.edu.au)
