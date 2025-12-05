a) Descripción del problema que estás modelando
La conexiones peatonales y transporte “rápido” que existe entre 6 puntos en mi colonia, con el objetivo de mapear y analizar la accesibilidad y sus posibles rutas.

b) Qué representa cada vértice
Los vértices (6 en total) representan los siguientes lugares o puntos clave:
•	Casa
•	ParadaCamion (Parada de Autobús)
•	TiendaSara (Tienda Local)
•	AlbercaCE (Alberca)
•	Smart (Tienda de supermercado)
•	Oxxo (Tienda de conveniencia)

c) Qué representa cada arista
Las aristas representan un camino directo entre dos lugares
Las aristas son: 
Casa a ParadaCamion
Casa a TiendaSara
Casa a AlbercaCE
ParadaCamion a AlbercaCE
TiendaSara a Smart
Smart a Oxxo
Oxxo a AlbercaCE

d) Diagrama del grafo
 
e) Análisis: grados, conexidad, ciclos si existen
| Vértice   | Grado  | Significado en el contexto |
|----------|----------|--------|
| Casa   | 3  | Lugar con alta accesibilidad a otros 3 puntos.  |
| AlbercaCE   | 3| Conexión a 3 lugares clave, siendo un nudo importante.  |
| ParadaCamion   | 2    | Conecta la Casa y la Alberca.  |
| TiendaSara| 2  | Conecta la Casa y el Smart.  |
| Smart  | 2    | Conecta TiendaSara y Oxxo.  |
| Oxxo    | 2   | Conecta Smart y AlbercaCE.  |

El grafo es conexo. Hay un camino entre cualquier par de vértices.
Si existen 2 ciclos, los cuales son: 
Ciclo Corto (4 vértices): AlbercaCE  Oxxo a Smart  TiendaSara  Casa AlbercaCE
Ciclo Largo (6 vértices): Casa   TiendaSara  Smart  Oxxo  AlbercaCE   ParadaCamion  Casa

f) Una pregunta interesante que puedas responder con tu grafo
Si se cierra temporalmente el camino entre Casa y AlbercaCE por obras públicas, ¿Cuántas alternativas quedan para ir de la Casa a la AlbercaCE, y cuál seria la ruta más larga?
Conexiones Alternativas (Caminos):
•	Ruta 1 (3 pasos): Casa a ParadaCamion a AlbercaCE
•	Ruta 2 (4 pasos): Casa a TiendaSara a Smart a Oxxo a AlbercaCE
Ruta Más Larga es :La ruta más larga es la Ruta 2 con 4 pasos.

