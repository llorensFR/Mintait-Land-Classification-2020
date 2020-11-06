# Minsait-Land-Classification
Datahack 2020 - Reto Minsait Land Classification

**Objetivo**: encontrar mejor modelo de clasificación automática de suelos en base a las imágenes proporcionadas por el satélite Sentinel II del servicio Copernicus de la Agencia Espacial Europea.

**Dataset**: listado de superficies sobre las que se han recortado la imagen de satélite y se han extraído una serie de características de sus geometrías:

EL dataset contiene un total 58 variables + 1 clase de clasifiación: 

- Las 6 primeras relativas a la identificación de los registros. 

- Las 44 siguientes están conformadas por la información extraída y tratada de las imágenes satelitales mediante 4 canales (R, G, B y NIR), correspondientes a las bandas de color rojo, verde y azul, y el infrarrojo cercano. El valor mostrado corresponde a la intensidad por deciles en cada imagen. Estas variables empiezan con la letra “Q”.

- Las 8 últimas variables son distintas referencias geométricas y relativas al entorno (geometría del edificio, métricas geométricas generadas automáticamente -GEOM-, metros cuadrados, año construcción y nº de plantas de los edificios del entorno).

- La última variable es la clase a predecir (únicamente en el fichero de entreno)
