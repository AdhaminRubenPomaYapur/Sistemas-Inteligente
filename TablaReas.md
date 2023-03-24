# ***REAS***
> ## ***Rendimiento***
>> Metrica con la cual se evalua el problema y se dan parametros a seguir como un tipo de hipotesis.
>> - Cuales son las medidas de rendimiento que se utilizan para evaluar el exito del sistema?
>> - Cuales son los objetivos de desempeño del sistema?
> ## ***Entorno***
>> El entorno es la informacion abstracta del mundo al que se enfrenta.
>> - En que tipo de entorno opera el sistema?
>> - Cuales son las condiciones ambientales, fisicas o sociales que el sistema debe tener en cuenta?
>> ## ***Observable***
>>> Si es capaz de mirar su entorno.
>> ## ***No Observable***
>>> Si no es capaz de mirar su entorno.
>> ## ***Parcialmente Observable***
>>> Que se pueden o no ver las cosas.
>>
>> ---
>> ## ***Deterministico***
>>> Cuando ya se conoce el estado y los resultados a ese cambio.
>> ## ***Estocastico***
>>> Es cuando el resultado es ramdom lo cual el agente no lo puede determinar.
>>
>> ---
>> ## ***Competitivo***
>>> Es cuando compite con otro agente para optimizar sus salidas.
>> ## ***Colaborativo***
>>> Cuando varios agentes cooperan para sacar un resultado.
>>
>> ---
>> ## ***Mono agente***
>>> Que solo trabaja un agente en el entorno.
>> ## ***Multi Agente***
>>> Que trabajan varios agente en el entorno.
>>
>> ---
>> ## ***Dinamico***
>>> Un entorno que cambia constantemente se considera dinamico.
>> ## ***Estatico***
>>> Un entorno que no cambia de estado es considerado estatico.
>>
>> ---
>> ## ***Discreto***
>>> Consiste en un numero finito de numeros que determinan una salida.
>> ## ***Continuo***
>>> Consiste en infinito donde los numeros no pueden ser la unidad.
>>
>> ---
>> ## ***Episodico***
>>> No hay dependencia entre un hecho y otro, los entornos pueden ser diferentes.
>> ## ***Secuencial***
>>> Las decisiones del pasado afectaran el presente y futuro.
>>
>> ---
> ## ***Actuadores***
>> Son los que reciben la informacion y lo pueden o no almacenar en su bitacora de informacion y por el cual toman una decision.
>> - Que tipo de actuadores utiliza el sistema para interacturar con el entorno?
>> - Como se controlan los actuadores?
> ## ***Sensores***
>> Son los que captan la informacion del entorno.
>> - Que sensores utiliza el sistema para percibir el entorno?
>> - Como se procesan y se interpretan los datos de los sensores?
---
# ***Racionalidad***
> La capacidad de tomar decisiones en funcion a la informacion que tenga disponible, entre mas informacion reciba del entorno mejor sera su respuesta.
> 
> El entorno necesita un ratio.

# ***Agente***
> ## ***Concepto***
>> Es una entidad capaz de percibir su entorno, procesar tales percepciones y responder o actuar en su entorno de manera racional.
> ## ***Tipos de Agente***
> 1. ### ***Reaccion simple o Reactivo***
>> - Se enfoca en tomar decisiones basadas en la informacion que recibe e tiempo real de su entorno y ajustadas a sus reglas de decision.
> 2. ### ***basado en busqueda o metas - Basado en objetivos***
>> - Se enfoca en alcanzar un objetivo particular en un entorno determinado. Tiene una representacion interna del estado del mundo.
> 3. ***Agente basado en Modelos:***
>> - Mantiene una representacion interna del mundo y utiliza esta representacion para predecir como puede evolucionar el mundo en el futuro.
> 4. ### ***Agente basado en conocimiento***
>> - Utiliza conocimiento especificos para tomar decisiones en un entorno determinado. Puede ser dado por expertos, o por aprendizaje automatico.
> 5. ### ***Agente basado en aprendizaje:***
>> - Aprende de la experiencia en un entorno determinado. Utiliza los datos recopilados para mejorar su rendimiento y tomar decisiones precisas en el futuro.
> 6. ### ***Agente Hibrido:***
>> - Combina distintos enfoques de los tipos de agentes para tareas complejas.
---
# ***Busqueda No Informada:***
> - Es una tecnica de resolucion de problemas que utiliza algoritmos para explorar el espacio de busqueda sin tener en cuenta ninguna informacion especifica del problema.
>> - BFS (Primero en Amplitud) (Breadth-first search)
>> - UCS (Costo uniforme) (Uniform-cost search) 
>> - DFS (Primero en profundidad) (Depth-first search)
>> - DLS (Profundidad Acotada) (Depth-limited search)
>> - IDDFS (Primero en profundidad con descenso iterativo) (Iterative deepening depth-first search)
>> - Busqueda bidireccional (Bidirectional search)
# ***Busqueda Informada:***
> - Es una tecnica de resolucion de problemas que utiliza informacion especifica del problema para guiar la busqueda de soluciones mas prometedoras. Es util cuando se dispone de informacion especifica.
>> - Busqueda voraz (Greedy best-first search)
>> - A* (A* search)
>> - Busqueda heuristica de memoria acotada (Memory-bounded heuristic search)
# ***Busqueda local:***
> - Es una tecnica de optimizacion que busca una solucion optima en un espacio de busqueda iteratiamente mejorando una solucion atual a traves de cambios locales.
>> - Escalada simple (Hill-climbing search)
>> - Recocido simulado (Simulated annealing)
>> - Haz local (Local-beam search)
>> - Algoritmos geneticos
>> - Mini-max
>> - Poda alfa-beta (Alpha-beta pruning)