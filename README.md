## ⚙️ Installation
```bash
pip install pandas numpy matplotlib plotly scikit-learn mlxtend dash
```

## 🚀 Lancer le notebook
1. Ouvrir `earthquake_notebook.ipynb` dans Jupyter ou Google Colab
2. Placer le dataset dans `data/earthquake_data.csv`
3. Exécuter toutes les cellules (`Run All`)
4. Le dashboard se lance sur `http://127.0.0.1:8050`

## 📊 Indicateurs construits
| # | Type | Description |
|---|------|-------------|
| Q1 | Groupby | Magnitude moyenne et nombre d'événements par continent |
| Q2 | Pattern mining | Règles d'association Apriori (alerte × tsunami × magnitude) |
| Q3 | Temporel | Fréquence mensuelle des séismes + rolling average 3 mois |
| Q4 | Spatial | Clustering DBSCAN des hotspots sismiques mondiaux |