# Tarea 8.2: Uso de Stacks para análisis de datos de RADseq
## Karen Yoselin Jiménez Cedillo, 2020

Los parametros utilizados para el análisis de datos de RADseq en Stacks para este trabajo fueron el uso de un valor de distancia permitida entre stacks (`M`) de 2, un valor de profundidad mínima de cobertura (`m`) de 3 y para el valor de distancia permitida entre loci catalogados (`n`) se utilizaron los valores del 1 al 3. Respecto a los resultados encontrados para estos respectivos valores, podemos encontrar la información resumida en la Tabla 1. 

De manera general, podemos observar que se encuentra una mayor cantidad de loci y de SNP cuando se utiliza un valor de distancia permitida entre loci catalogados (`n`) de 3. Sin embargo, debemos considerar que entre más grande sea el valor de `n`, es permitido un mayor error en permitir que loci cercanos se agrupen y creen un loci grande y erroneo. Por lo tanto, considero que utilizar un valor de n=2 es eficiente, ya que la cantidad de loci y SNP no se ve tan reducida y el error se disminuye. Además, el manual de Stacks recomienda usar el mismo valor en `n` y `m` 

Sin embargo, este solo es un pequeño ejercicio con una muestra de datos reducida, en un estudio real utilizar parámetros tan rigurosos podría llevar a la pérdida de mucha información. Al contrario, parámetros flexibles podrían llevar a la interpretación de datos incorrectos.  


| M | n | m | # de loci | # de SNP |
|:-:|:-:|:-:|:---------:|:--------:|
| 2 | 1 | 3 |   36986   |   25667  |
| 2 | 2 | 3 |   37819   |   28327  |
| 2 | 3 | 3 |   38096   |   30366  |

#### *Tabla 1*. Resumen de los resultados obtenidos 
#### al utilizar Stacks con las muestras seleccionadas 
#### dependiendo del número de distancia permitida 
#### entre loci catalogados.
