# Ejemplo reproducible de PCA — Brereton

Artículo: Brereton (2023), *Principal components analysis with several objects and variables*, *Journal of Chemometrics*, DOI: 10.1002/cem.3408.

Para ejecutar:

```bash
python -m pip install -r requirements.txt
jupyter notebook PCA_Brereton.ipynb
```

El notebook lee `datos/datos_tabla1.csv` y las tablas de referencia transcritas en `datos/`. Reproduce las Figuras 1–9 en `figures/` y exporta resultados numéricos a `results/`.

El PCA se calcula sin centrar mediante SVD, de acuerdo con el artículo.
