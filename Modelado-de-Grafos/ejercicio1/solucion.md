EJERCICIO 1 (35 puntos): SISTEMA DE VUELOS
Una aerolínea tiene los siguientes vuelos (solo ida):

| Origen   | Destino  | Precio |
|----------|----------|--------|
| México   | Cancún   | $1500  |
| México   | Monterrey| $1200  |
| Cancún   | Miami    | $3500  |
| Monterrey| Houston  | $2800  |
| Houston  | Miami    | $1800  |
| Miami    | México   | $4000  |

a)	Dibuja el grafo (con flechas y precios)

b)	¿Es dirigido o no dirigido? ¿Es ponderado?
Es dirigido porque los vuelos son de solo ida.
Si es ponderado, porque cada arista tiene un valor asociado, que viene siendo el precio del vuelo.

c)	Calcula el grado de entrada y salida de cada ciudad
Ciudad    ,Grado de Salida (Vuelos que salen),Grado de Entrada (Vuelos que llegan)
México,"2 (a Cancún, a Monterrey)          ",1 (de Miami)                        
Cancún,1 (a Miami)                        ,1 (de México)                        
Monterrey,1 (a Houston)                    ,1 (de México)                        
Miami  ,1 (a México)                      ,"2 (de Cancún, de Houston)            "
Houston,1 (a Miami)                        ,1 (de Monterrey)                      

d)	¿Cuál ciudad tiene más vuelos salientes?
La ciudad con más vuelos salientes es México, con 2 vuelos.

e)	Encuentra la ruta más barata de México a Miami
Las posibles rutas de México a Miami son:
México a Cancún a Miami = Costo: $1500 + $3500 = $5000
México a Monterrey a Houston a Miami = Costo: $1200 + $2800 + $1800 = $5800
La ruta más barata es México a Cancún a Miami, con un costo de $5000.

f)	¿Existe algún ciclo? Si sí, descríbelo
Sí, existe un ciclo. Un ciclo es un camino que comienza y termina en el mismo vértice, sin repetir aristas.
•	Ciclo: Miami a México a Monterrey a Houston a Miami, O bien, Miami a México a Cancún a Miami.

