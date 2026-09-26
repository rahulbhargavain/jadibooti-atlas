# Jadibooti atlas of Uttarakhand

**Live site:** [https://rahulbhargavain.github.io/jadibooti-atlas/](https://rahulbhargavain.github.io/jadibooti-atlas/)

Open `index.html` in a browser (works offline). Tabs: Atlas (altitude chart, microclimates, zone map), Calendar (phenology), Plants, Uses & evidence, Crops & GI, Formulations, Sources.

| File | What |
| --- | --- |
| `data_plants.py` | 45 species (names, altitude, habitat, microclimate, phenology, cultivation, economics, conservation, uses, safety, GI) and 14 classical formulations with their Himalayan ingredients |
| `data_evidence.py` | curated evidence notes and grades (read from the PubMed titles) |
| `data_crops.py` | hill crops and cultivars (ICAR-VPKAS VL series etc.), the 26 registered Uttarakhand GIs |
| `evidence.py` | PubMed counts via NCBI E-utilities → `evidence.json` (`python evidence.py` to refresh all, `python evidence.py kutki atis` for some) |
| `climate.py` | ERA5 monthly profiles for nine altitude sites → `climate.json` |
| `build.py`, `template.html` | builds the page |
| `pit.sqlite`, `raw/` | point-in-time store and cached sources (TERI/SMPB report, NMHS SOP, PubMed, climate, terrain) |

Primary sources: TERI (2013) report for the Uttarakhand State Medicinal Plants Board with HRDI and CAP data; NMHS cultivation SOPs; HAPPRC; CSIR-CIMAP / Aroma Mission; IUCN and CITES; GI Registry; ICAR-VPKAS.

Not medical advice: the page maps plants and research volume; it doesn't recommend treatments.

