# Problema 2 - TP N°1 - AAII

## **Enunciado**
En el siguiente problema, se presenta un conjunto de datos sobre diferentes variedades de frijoles secos. El objetivo es desarrollar un modelo de clasificación que pueda distinguir entre siete variedades registradas de frijoles secos, utilizando características como forma, tamaño, tipo y estructura. Se utilizó un sistema de visión por computadora para obtener imágenes de los granos de frijol y luego se llevó a cabo la segmentación y extracción de características para obtener un total de 16 atributos, incluidas 12 dimensiones y 4 formas.

#### Dataset
El dataset proporcionado incluye las siguientes variables para cada paciente:
* **Area (A)**: El área de una zona de frijol y el número de píxeles dentro de sus límites.
* **Perimeter (P)**: La circunferencia del frijol se define como la longitud de su borde.
* **Major axis length (L)**: La distancia entre los extremos de la línea más larga que se puede dibujar desde un frijol.
* **Minor axis length (l)**: La línea más larga que se puede dibujar desde el frijol mientras está perpendicular al eje principal.
* **Eccentricity (Ec)**: Excentricidad de la elipse que tiene los mismos momentos que la región.
* **Convex area (C)**: Número de píxeles en el polígono convexo más pequeño que puede contener el área de una semilla de frijol.
* **Equivalent diameter (Ed)**: El diámetro de un círculo que tiene el mismo área que el área de una semilla de frijol.
* **Extent (Ex)**: La relación de los píxeles en el cuadro delimitador con respecto al área del frijol.
* **Solidity (S)**: También conocida como convexidad. La relación de los píxeles en la envoltura convexa con respecto a los que se encuentran en los frijoles.
* **Compactness (CO)**: Mide la redondez de un objeto: Ed/L.
* **ShapeFactor1 (SF1)**.
* **ShapeFactor2 (SF2)**.
* **ShapeFactor3 (SF3)**.
* **ShapeFactor4 (SF4)**.
* **Class**: Seker, Barbunya, Bombay, Cali, Dermosan, Horoz y Sira.


#### Objetivo
Utilizando el conjunto de datos proporcionado, el objetivo es construir un modelo de clasificación que pueda predecir con precisión la variedad de frijol seco basándose en las características mencionadas anteriormente. Se emplearán técnicas de aprendizaje automático, específicamente redes neuronales, para entrenar y evaluar el modelo.

Además, se requiere que el alumno calcule y agregue al conjunto de datos las siguientes características:
* **Aspect ratio (K)**: Relación entre la longitud del eje mayor (L) y la longitud del eje menor (l) .
* **Roundness (R)**: Se debe calcular utilizando la fórmula (4piA)/(P^2).

Estas nuevas características calculadas se utilizarán como parte del conjunto de datos para el entrenamiento y evaluación del modelo de clasificación.

## **Recursos**
### 'Problema 2.ipynb'
Todo los algoritmos necesarios para resolver el problema se encuentra en este archivo.
