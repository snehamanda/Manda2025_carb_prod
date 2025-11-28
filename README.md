# Carbonate Production Analysis Repository

This repository contains code and notebooks for analyzing carbonate production using lbf (large benthic foraminifera) data.

## Repository Contents

### 1. Jupyter Notebooks (`.ipynb`)
Each `.ipynb` file corresponds to a model for carbonate production.  
- **Input file required:** `station_lbf.csv`  
  - `station` should be replaced with the corresponding sampling station name (all lowercase).  
  - `lbf` should be replaced with the corresponding lbf taxon (all lowercase).  

#### Sampling Stations
- akhziv  
- shikmona  
- nahsholim  
- palmachim  

#### LBF Taxa
- amphis  
- soritids  
- textularia
- peneroplis


## Notebook Table

| Notebook File           | Station     | LBF Taxon    |
|------------------------|------------|-------------|
| akhziv_amphis.ipynb     | akhziv     | amphis      |
| akhziv_soritids.ipynb   | akhziv     | soritids    |
| akhziv_textularia.ipynb | akhziv     | textularia  |
| akhziv_peneroplis.ipynb | akhziv     | peneroplis  |
| shikmona_amphis.ipynb   | shikmona   | amphis      |
| shikmona_soritids.ipynb | shikmona   | soritids    |
| shikmona_textularia.ipynb | shikmona | textularia  |
| shikmona_peneroplis.ipynb | shikmona | peneroplis  |
| nahsholim_amphis.ipynb   | nahsholim | amphis      |
| nahsholim_soritids_05.02.2025.ipynb | nahsholim | soritids    |
| nahsholim_textularia.ipynb | nahsholim | textularia|
| nahsholim_peneroplis.ipynb | nahsholim | peneroplis|
| palmachim_amphis.ipynb   | palmachim | amphis      |
| palmachim_soritids.ipynb | palmachim | soritids    |
| palmachim_textularia.ipynb | palmachim | textularia|
| palmachim_peneroplis.ipynb | palmachim | peneroplis|

---

### 2. R Notebooks (`.rmd`)
- These files are used to reproduce figures corresponding to the figure numbers in the table  
- Data for the Rms files, are avaialbel in the suplementary Material of the corresponding publication

---

### How to Use
1. Clone the repository:  
```bash
git clone https://github.com/yourusername/your-repo.git

