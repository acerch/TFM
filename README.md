# TFM
Comparación exploratoria de herramientas bioinformáticas para el análisis de datos de Visium HD

Visium HD es una tecnología reciente y en rápida adopción, pero aún carece de un enfoque estándar 
—particularmente en lo relativo al tamaño de bin a utilizar— y de herramientas bioinformáticas 
consolidadas para el análisis de sus datos. En este trabajo se busca contribuir a esa discusión 
mediante la evaluación comparativa de distintos pipelines aplicados a un dataset público de tejido 
mamario humano con carcinoma ductal in situ (DCIS).

Concretamente, se analiza el desempeño de Bin2cell (utilizando bins de 2 µm) en combinación con Scanpy, 
para llevar a cabo un análisis posterior a nivel de célula única. Estos resultados se comparan con los 
obtenidos mediante el uso de bins agrupados de 8 µm —la estrategia recomendada por 10x Genomics— empleando 
los pipelines convencionales de Scanpy y Seurat, que permiten una resolución aproximada a single-cell.

Referencias bibliográficas: 
1. 10X Genomics. Human Breast Cancer (Fresh Frozen), Visium HD WT Panel Gene Expression dataset analyzed by Space Ranger 3.1.1 [Internet]. 2024 [citado 23 de junio de 2025]. Disponible en: https://www.10xgenomics.com/datasets/visium-hd-cytassist-gene-expression-human-breast-cancer-fresh-frozen
2. Teichlab/bin2cell [Internet]. Teichmann Group; 2025 [citado 24 de junio de 2025]. Disponible en: https://github.com/Teichlab/bin2cell
3. Teichlab. N2_demo_analysis_crc_public - Bin2cell [Internet]. [citado 24 de junio de 2025]. Disponible en: https://nbviewer.org/github/Teichlab/bin2cell/blob/main/notebooks/N2_demo_analysis_crc_public.ipynb
4. Palla G. Analysis and visualization of spatial transcriptomics data — scanpy-tutorials documentation [Internet]. [citado 24 de junio de 2025]. Disponible en: https://scanpy-tutorials.readthedocs.io/en/latest/spatial/basic-analysis.html
5. Satija Lab. Analysis, visualization, and integration of Visium HD spatial datasets with Seurat [Internet]. [citado 23 de junio de 2025]. Disponible en: https://satijalab.org/seurat/articles/visiumhd_analysis_vignette#unsupervised-clustering
6. Bartlett A, Mistry M, Gammerdinger W. HBCtraining-Spatial transcriptomics Nanocourse Visium HD lesson. [Internet]. GitHub; 2025 Feb 26. [citado 23 de junio de 2025]. Disponible en: https://github.com/hbctraining/spatial_nanocourse/blob/main/lessons/visium_hd.md
