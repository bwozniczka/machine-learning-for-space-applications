# SVD Lab — Satellite Images

Lab exploring **Singular Value Decomposition (SVD)** on satellite imagery (urban / forest / ocean).

## How to run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook algebra.ipynb
```

Or open `algebra.ipynb` in VS Code / Cursor with the `.venv` kernel.

## Data

| File | Terrain | Region |
|---|---|---|
| `data/urban.jpeg` | Urban | Warsaw |
| `data/forest.jpeg` | Forest | Amazon (near Manaus) |
| `data/ocean.jpeg` | Ocean | Mid-Atlantic |
| `data/scene.jpeg` | Urban (alias) | same as urban |

Satellite tiles from ESRI World Imagery (educational use).

## What’s in the notebook

1. SVD on urban image + singular-value plot  
2. Reconstructions for several `k` — how many components are enough?  
3. Largest `k` vs components `10 … k+10` (skipping first 10)  
4. Comparison across terrains + observations  

Notebook outputs (plots/images) are saved so results are visible on Git without re-running.
