# proyectoingsoft
proyecto final de ingeniería de software

Este programa realiza el ajuste de poligonales topograficas cerradas y abiertas 
## LECTURA DE DATOS 
la lectura de datos se realiza desde un archivo plano con un formato predefinido. 
>  El tipo de poligonal se ingresa por pantalla 

>La ruta del archivo con las mediciones de la poliognal se digita en pantalla 

## VALIDACIONES
el programa  valida si el archivo con las mediciones cumple con el formato que el programa lee
## AJUSTES 

### poligonal cerrada
Si la poligonal es cerrada los posibles metodos de ajustes ceran:

-metodo de brujula
-metodo de transito

>se solicitara por pantalla al usuario las coord de los puntos de la linea de referencia

###poligonal abierta
si la poligonal es abierta el metodo de ajuste sera **crandall*

>Se solicitara por pantalla al usuario las coord de los puntos de la linea de referencia de inicio y fin 


##SALIDA
los resultados de los calculos y los ajustes se guardan en un archivo plano en la misma ruta del archivo de entrada

##GRAFICAS
LA poligonal se dibuja a traves de uno de los siguientes metodos: 

-Un arhivo **Geojson** o **Json**
- En consola a traves de una libreria grafica
-en un archivo CAD a traves de una libreria externa 

[universidad distrital](https://www.udistrital.edu.co)
