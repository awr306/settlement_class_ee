# settlement_class_ee
The process of segregating settlements from other structures in both urban and rural regions. The GEE (Google Earth Engine) utilized the Random Forest model to evaluate built-up areas and residential areas. This model comprises approximately 19 predictors derived from multisource satellites. An experiment in the Banyumas, Cilacap, and Tegal regions of Central Java, Indonesia, successfully differentiated between four land cover categories, namely 1 - others (including vegetation), 2 - buildings, 3 - settlements, and 4 - water bodies.

Link GEE [Settlements_Identification](https://code.earthengine.google.com/4f8d79a5e6fa721dbca93b92ac88bce5).

## Requirements
Users might need to :
- determine point samples per class (1 - 4)
- modify boundary area
- modify the path directory
- modify DEM file (The DEM data in this repository is DEMNAS Indonesia obtained from Indonesia Geospatial Authority https://tanahair.indonesia.go.id/demnas/#/)

## Citing
```
@article{Rudiastuti2022,
  author = {Rudiastuti, A.W. and Lumban-Gaol, Y. and Silalahi, F.E.S. and Prihanto, Y. and Pranowo, W.S.},
  doi = {10.30630/joiv.6.1.873},
  ISSN = {25499904},
  journal = {International Journal on Informatics Visualization},
  keywords = {Google Earth Engine (GEE), Land Use/Land Cover (LULC), Machine learning, Random forest, Sentinel, Settlement},
  number = {1},
  title = {{Implementing Random Forest Algorithm in GEE: Separation and Transferability on Built-Up Area in Central Java, Indonesia}},
  volume = {6},
  year = {2022}
}
```
