# FDS-2023-1-CC52
Trabajo Final de Fundamentos de Data Science 2023-1

## Objetivo del proyecto
Los objetivos concretos de este proyecto de analítica para Peru_bike son identificar perfiles de clientes propensos a comprar bicicletas, implementar un scoring de venta, comprender las preferencias y necesidades de los clientes, analizar los patrones de comportamiento de compra y mejorar la segmentación de clientes.

## Participantes
- Jak Cristian Campos Espinoza
- Sebastian Gabriel Cataño Justiniani
- Gonzalo Alejandro Jurado Garay
- Alejandro Olaf López Flores

## Descripción del conjunto de datos
| Variable | Descripción |
| --- | --- |
| `ID` | El ID del usuario. |
| `Marital Status` | El estado marital del usuario. Puede ser: casado(`Married`) o soltero(`Single`). |
| `Gender` | El género del usuario. Puede ser: masculino(`Male`) o femenino(`Female`). |
| `Income` | Los ingresos del usuario en un cierto momento. |
| `Children` | El numero de hijos que el usuario tiene. |
| `Education` | Antecedentes educativos del usuario. Puede ser: bachillerato(`Bachelors`), titulación(`Graduate Degree`), preparatoria(`High School`), universidad parcial(`Partial College`) o preparatoria parcial(`Partial High School`). |
| `Occupation` | Trabajo o ocupación del usuario. Puede ser: eclesiastica(`Clerical`), administrativa(`Management`), manual(`Manual`), professional(`Professional`) o manual especializado(`Skilled Manual`). |
| `Home Owner` | Si el usuario tiene o no una casa propia. |
| `Cars` | El número de autos que tiene el usuario. |
| `Commute Distance` | La distancia entre la casa del usuario y su compañia. Hay 5 categorias: 0-1 Milla(`0-1 Miles`), 1-2 Millas(`1-2 Miles`), 2-5 Millas(`2-5 Miles`), 5-10 Millas(`5-10 Miles`) y 10+ Millas(`10+ Miles`). |
| `Region` | La región del usuario. Puede ser: Europa(`Europe`), Norte América(`North America`) o Pacífico(`Pacific`). |
| `Age` | La edad del usuario. |
| `Purchase` | Si es que el usuario a comprado una bicicleta o no. |

## Conclusiones

En base a los requerimientos, se alcanzan estas conclusiones:

- Se puede decir que la mayoría de los clientes, a pesar de que compraran una bicicleta o no, reciben un ingreso aproximado de 55000.
- La cantidad total de ingresos recibidos por clientes casados es mayor al de clientes solteros, lo cual puede deber a que aquellos casados necesitan más plata para sus familias.
- Clientes con una educación de nivel Bachelors son los que menos tienen hijos, pero en general el número total de clientes sin hijos es considerablemente alto.
- Clientes con una ocupación profesional son los que más tienen un vehículo de transporte, pero incluso así este no es un número muy alto al considerar la cantidad de clientes en el dataset.
- La edad promedio entre clientes que tienen una propiedad o no es relativamente parejo, con una diferencia de alrededor de un año.

## Licencia de uso
