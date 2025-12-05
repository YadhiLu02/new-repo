EJERCICIO 2 (35 puntos): RED DE COMPUTADORAS
Una oficina tiene la siguiente red:

- El Router principal conecta con: Servidor, Switch1, Switch2
- Switch1 conecta con: PC1, PC2, Impresora1
- Switch2 conecta con: PC3, PC4, Impresora2
- El Servidor conecta con: Router (ya mencionado)

a)	Dibuja el grafo de la red

b)	¿Cuántos vértices y aristas tiene?
vértices (Nodos): 10 (Router,Servidor,Switch1,Switch2,PC1,PC2,Impresora1,PC3,PC4,Impresora2).
Aristas (conexiones): 9.
- Router  Servidor (1)
- Router  Switch1 (2)
- Router  Switch2 (3)
- Switch1  PC1 (4)
- Switch1  PC2 (5)
- Switch1  Impresora1 (6)
- Switch2  PC3 (7)
- Switch2  PC4 (8)
- Switch2  Impresora2 (9)

c)	¿Es conexo? ¿Qué significa esto para la red?
Si, el grafo es conexo, y significa que existe un camino entre cualquier par de dispositivos en la red, asegurando que todos los dispositivos puedan comunicarse entre sí, directa o indirectamente.

d)	¿Es un árbol? Justifica
Sí, si es un árbol, ya que cumple con las condiciones de ser conexo y acíclico.

e)	Si se desconecta el Router, ¿cuántas componentes conexas quedan?
Si eliminamos el Router (y sus aristas), el grafo se divide en varias partes aisladas. Quedan 3 componentes conexas:
El Servidor (aislado).
Switch1 y sus 3 dispositivos finales ({Switch1, PC1, PC2, Impresora1}).
Switch2 y sus 3 dispositivos finales ({Switch2, PC3, PC4, Impresora2}).

f)	¿Cuál es el dispositivo más crítico de la red? (si falla, más dispositivos quedan aislados)
El dispositivo más crítico es el Router.
El Router es el vértice de corte con mayor impacto. Al fallar, el grafo se divide en el mayor número de componentes conexas (3) y aísla la comunicación para la mayoría de los dispositivos (el Servidor y todos los dispositivos conectados a los Switches), demostrando su alta centralidad en la red.

