# Tarea 1.2: Modelado de Grafos

## Información
- **Nombre:** [YADHIRA LUNA CARRILLO ]
- **Fecha:** [05 / DICIEMBRE / 2025]

## Ejercicio 1: Sistema de Vuelos
[Resumen de tu solución:
Este ejercicio modela un sistema de vuelos de una aerolínea como un grafo dirigido y ponderado.
Las ciudades son los vértices y los vuelos son las aristas, con los precios como pesos.
- Modelo: Grafo Dirigido (vuelos solo ida) y Ponderado (precios).
- Análisis de Grados: La ciudad de México tiene el mayor grado de salida (2 vuelos), y Miami tiene el mayor grado de entrada (2 vuelos).
- Ruta Más Barata (México a Miami): La ruta más económica es México --> Cancún --> Miami con un costo total de $5000.
- Ciclos: Existe un ciclo, por ejemplo: Miami --> México --> Monterrey --> Houston --> Miami]
![Diagrama](ejercicio1/Diagrama1.png)

## Ejercicio 2: Red de Computadoras
[Resumen de tu solución:
Este ejercicio modela una red de oficina como un grafo no dirigido. Los dispositivos (Router, Servidor, PCs, Switches, Impresoras) son los vértices (10 en total) y los cables de conexión son las aristas (9 en total).
- Modelo: El grafo es conexo, lo que asegura la comunicación entre todos los dispositivos. Además, el grafo es un árbol porque es conexo y acíclico (no tiene ciclos). * Dispositivo
- Crítico: El dispositivo más crítico es el Router.
- Análisis de Fallas: Si el Router falla (se desconecta), la red se divide en 3 componentes conexas (el Servidor, el grupo del Switch 1, y el grupo del Switch 2), aislando la comunicación para la mayoría de los dispositivos]
![Diagrama](ejercicio2/Diagrama2.png)

## Ejercicio 3: [Sistema de rutas en mi colonia]
[Resumen de tu solución:
Este ejercicio modela las conexiones de acceso y transporte entre 6 puntos de interés en un barrio o colonia.
- Vértices: Casa, Parada de Autobús, TiendaSara, AlbercaCE, Smart, y Oxxo.
- Modelo: Grafo no dirigido15. El grafo es conexo (se puede ir de cualquier punto a cualquier otro)16. * Análisis de Grados: Los puntos con mayor accesibilidad (Grado 3) son la Casa y la AlbercaCE.
- Ciclos: El grafo contiene ciclos, incluyendo uno largo que pasa por todos los 6 vértices.
- Ruta Alternativa: Si se cierra el camino directo Casa <--> AlbercaCE, existen 2 rutas alternativas para ir de la Casa a la AlbercaCE, siendo la más larga la de 4 pasos (Casa --> TiendaSara --> Smart --> Oxxo --> AlbercaCE).
]
![Diagrama](ejercicio3/Diagrama3.png)
