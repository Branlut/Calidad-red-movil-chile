# Exploracion Compañias de telefonia
## Descripción
- El data set cuenta con los datos de calidad de red movil de las compañias de telecomunicaciones de Chile correspondientes al periodo de Noviembre del 2018 y sus indicadores principales.

## Objetivos
- Evaluar el desempeño de las empresas 
- Identificar estaciones problematicas
- Desempeño por region
## Tecnologias
- Python
- Vs code
- pandas
- matplotlib
- scipy

## Hallazgos
- Los intentos de llamadas  con relacion a las llamadas exitosas son proporcionales esto quiere decir los servicios de comunicaciones son buenos ya que el numero de llamadas casi siempre son exitosas
- Con relacion a las llamadas interrumpidas se puede apreciar que son en menor numero que las exitosas y que estan no aumentan en gran medida al crecer el numero de llamadas
- La tasa de llamadas exitosas por region es casi identicas con diferencias decimales, lo que indica que el servicio que provee a las diferentes es bastante similar 
- La tasa de llamadas interrumpidas cuenta con la 9 y 16 region con las tasas mas altas. puede deberse a la locacion de estas o a la cantidad de estaciones que se encuentran en la zona lo que no permita un buen servicio
- La estacion que cuenta con la mayor tasa de interrupciones es la MRA3U13 lo cual es un 83.333333 %
- El tiempo de interrupcion por el otro lado la estacion SAEXFA cuenta con el el promedio mas alto con 25200 min 
- Con esto nos podemos dar cuenta que si bien el la tasa de interrupciones puede ser alta esto no indica que tiempo perdido por llamada sea alto
- La tasa de llamadas exitosas por empresa es casi igual teniendo diferencias decimales
- Por otro lado la tasa de interrupciones la empresa que cuenta con mas es la de movistar

## Hipótesis
h0 = La proporcion de llamadas establecidas con exito (PEE) es igual en zonas Urbanas y rurales

h1 = La proporcion de llamadas establecidas con exito (PEE) es diferente en zonas Urbanas y rurales
- Se rechazo la hipotesis nula, lo que quiere decir que el PEE difiere de las zonas urbanas y rurales, puede ser debido a la cantidad de estaciones o al tipo de configuracion de estas lo que proboca que las llamadas exitosas no sean iguales.
-
H0 = Las compañias tienen la misma proporción exitosa de llamadas (PEE)

H1 = Las compañias  tienen diferente proporción exitosa de llamadas (PEE)
- La hipotesis nula se rechazo esto quiere decir que a pesar de verse relativamente iguales en cuanto la proporcion de exito de llamadas no es igual para las compañias, por lo verificar la mas eficas o la que posee menos tiempo de interrupcion seria el factor para elegir alguna.

# Conclusiones

- Con la informacion diponible podemos apreciar que la tasa de llamadas de exitosa es casi identica en todas la compañias lo cual tambien se puede evidenciar en las diferentes regiones.
- El PEE Y PFE que corresponde a la proporcion de llamadas establecidas con exito y la porporcion de llamadas finalizadas con exito respectivamente es en promedio sobre el 97% lo que quiere decir que las compañias estan cumpliendo con el estadar el cual es porcetaje mencionado anteriormente 
- La region de La Araucania y la de Arica y Parinacota son las que presentan mas llamadas con interrupciones, lo que puede deberse al cantidad de estaciones que puedan tener
- La estacion que cuenta con la mayor tasa de interrupciones es la MRA3U13 lo cual es un 83.333333 %, lo cual puede deberse a una sobre saturacion o problemas en como esta intalada
- En cuanto al tiempo promedio de interrupcion es menor en general menos para la estacion SAEXFA lo que puede indicar algun probla tecnico que aumente el tiempo de interrupcion
- Las hipotesis probadas mostraron que las compañias y las zonas al verse similares en cuanto al PEE no se puede considarar iguales por lo que un factor para decidir puede ser la compañia mas eficas con respecto al PEE o la que tiene menor interrupciones 
