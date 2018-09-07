
# Resultados completos
### ¿Que hay en esta sección?
En esta sección se encuentran los resultados completos de todas las pruebas realizadas durante la realización del proyecto. 

## Formatos disponibles:

 1. csv
 2. xlsx
 3. ods
 5. html

## Estructura:
En el caso de los resultados en formato csv las diferentes pruebas (media de word embeddings, concatenación...) se dividen en subcarpetas. Dentro de cada subcarpeta podemos encontrar 3 archivos.

 - Métrica1: Descartamos los pares de palabras para los que el word/meta embedding no puede dar respuesta. Esta métrica no penaliza que no se pueda dar respuesta para un determinado número de pares de palabras.
 - Cobertura: Porcentaje de pares de palabras para los que cada word/meta embedding ha podido dar respuesta.
 - Métrica2: Multiplicación de los resultados obtenidos mediante la primer métrica y la cobertura. Esta métrica penaliza que no se pueda dar respuesta para un determinado número de pares de palabras.

El resto de formatos se encuentran en la subcarpeta "--- Resultados en otros formatos (ods, xlsx...) ---". La estructura es la misma que para el formato csv, salvo que en el caso de los formatos xlsx y ods los resultados se encuentran en un mismo archivos dividido en diferentes hojas. 


