'''
Created on 23 ene. 2017

@author: veronica
'''
from datetime import datetime, date, time, timedelta
def calculo(tarifa,tiempo):
    inicio=tiempo[0]
    fin=tiempo[1]
    #tasaDiaSem=tarifa[0]
    #tasaDiaFin=tarifa[1]
    diasDif=fin.day-inicio.day
    horasDif=fin.hour-inicio.hour
    minDif = fin.minute-inicio.minute
    return ((minDif+horasDif*60)//60 + diasDif*24)*tarifa + tarifa

def __init__():
    fecha1 = datetime(2017, 1, 5, 18, 7, 35)
    fecha2=datetime(2017,1,5,19,8,45)
    tarifa=100
    costo=calculo(tarifa,[fecha1,fecha2])
    print("El costo total es : ",costo)
    
__init__()
