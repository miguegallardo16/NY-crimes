# Estudio de datos sobre los delitos en Nueva York

Se usaron los siguientes atributos del conjunto de datos para el estudio:

- LAW_CAT_CD: indicador de nivel del delito (FELONY, MISDEMEANOR, VIOLATION). Al igual que otros atributos anteriores, no nos proporciona suficiente información para incluirlos en los análisis, con lo cual, lo descartamos.
- CMPLNT_TO_DT: fecha  (formato àmes/día/año)  de  registro  de resolución del delito. Si por algún motivo no se hubiera resuelto, este campo no tendría ningún valor asociado.
- SUSP_AGE_GROUP: grupo de edad de los sospechosos que cometieron el delito.
- SUSP_RACE: raza  o  etnia  a  la  que  pertenecen  los  sospechosos  que cometieron el delito.
- SUSP_SEX:sexo  de  los  sospechosos  que  cometieron  el  delito.  Los valores pueden ser hombre o mujer, representados por una letra.
- VIC_AGE_GROUP:grupo  de  edad  de  las  víctimas  que  se  vieron afectadas por el delito.
- VIC_RACE: raza o etnia a la que pertenecen las víctimasque se vieron afectadas por el delito.
- VIC_SEX:sexo de las víctimas que se vieron afectadas por el delito. Al igual  que  para  los  sospechosos,  los  valores  son  hombre  y  mujer, representados por una letra.
- BORO_NM: nombre  del  barrio  donde  se  ha  producido  el  delito.  Los valores  posibles  de  este  atributo  son:  BRONX,  BROOKLYN, MANHATTAN, QUEENS y STATEN ISLAND, es decir, cada uno de los barrios que componen la ciudad de Nueva York.


## Primero se hizo un heatmap para ver la correlacion entre los distintos atributos

![Heatmap](https://github.com/miguegallardo16/NY-crimes/blob/main/imagenes/heatmap.png?raw=true)
v
## Realizamos una clasificacion supervisada de esos datos

![Clasificacion](https://github.com/miguegallardo16/NY-crimes/blob/main/imagenes/clf.png?raw=true)

## Creamos un árbol de decisión para nuestro caso de estudio

![Arbol](https://github.com/miguegallardo16/NY-crimes/blob/main/imagenes/tree.png?raw=true)

A partir de aqui se realizó un estudio a partir de las imagenes de manera interactivo con dash.

Por ultimo se hizo un estudio geografico a partir de las imagenes.

![Arbol](https://github.com/miguegallardo16/NY-crimes/blob/main/imagenes/vic_race.png?raw=true)
![Arbol](https://github.com/miguegallardo16/NY-crimes/blob/main/imagenes/susp_race.png?raw=true)
![Arbol](https://github.com/miguegallardo16/NY-crimes/blob/main/imagenes/boro_nm.png?raw=true)

