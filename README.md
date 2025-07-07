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
