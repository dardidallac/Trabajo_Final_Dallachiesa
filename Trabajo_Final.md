# Trabajo Final

## Este es el trabajo final

codigo para importar todo


````python 
import scipy.stats as ss
import statsmodels.stats.power as smp
import numpy as np
from statsmodels.stats.power import TTestIndPower
import pandas as pd
import matplotlib.pyplot as plt
````


Lectura y show de la tabla

````
path = "C:/Users/dardo/Desktop/Curso_estadistica/Trabajo_Final/Trabajo_Final_Dallachiesa/Tabla_Plantas.csv"
legumes = pd.read_csv(path,sep=';')
legumes
````

## Hipotesis

Varias hipotesis (estaran bien??)

1) La altura promedio de *Glycine max* es significativamente mayor que *Phaseolus vilgaris*
(no hay diferencia o la altura es significativamente mayor)

2) No hay diferencia significativa en la temperatura media entre *Medicago truncatula* y *Glycine max*

3) La humedad tiene una correlación positiva con la altura de las leguminosas.
(no hay correlación o hay correlación entre la humedad y altura)

4) *Glycine max* tiene una mayor variabilidad en la altura en comparación con *Phaseolus vugaris*
