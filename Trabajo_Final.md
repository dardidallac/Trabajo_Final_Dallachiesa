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
rizobios = pd.read_csv(path,sep=';')
rizobios
````
