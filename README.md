# Tarea-5

## Cadenas de Marcov de tiempo continuo

Se modela también el tiempo pero, tambien va a cambiar entre estados de forma aleatoria y la transición dentro estados depende del estado actaul. Proveen un modelo secuencial que permite que resultados futuros depedan ude resultados previos. El siguiente estado depende del resultado actual, los estados están bien definidos, es una simplificación de la realidad.

Las transiciones pueden modelarse de manera probabilística y crucial conocer el estado actual, las cadenas de Marcov son un modelo de dependecia. 
Las cadenas de Marcov.
#### Las cadenas de Marcov tienen memoria. 
#### Capacidad de moverse entre estados.
Con cadenas de Marcov de orden uno es lo más común en la práctica pero, dependiendo la complejidad o el grado de presición se va subiendo el grado de la cadena de Marcov.

#### Propiedad de la falta de memoria.
Formalmente, es una probabilidad condicional de la forma
##### P(Xn = x | X0, . . . , Xn−1) = P(Xn = x | Xn−1), ∀n, ∀x

#### Deducción a partir de la distribución exponencial (Pámetros importantes: Estados y transiciones)
A veces nos impoorta seber el tiempo de transición de los estados casi parecido al proceso de Poisson, pero lo que se busca el la permanencia en un estado , cual es la probabilidad de pasar de estado a otro, esto se refiere a la transición.
Va representar un tiempo de vida la distribución exponencial representa esto. Un ejemplo la vida util de un compenente va a depender de su vida útil.

##### Densidad de la variable mínima de un conjunto de variables aleatorias
Son independientes pero, no son identicamente distribuidas. Ejemplo, si se compra un carro nuevo y todos los componenetes están funcionando. N componentes se conectan como el carro nuevo ese es t=0 e inician su operación conjunta. Sea M es el tiempo mínimo de todos los tiempos de vida de todos los componentes, del que el primer comente falle.
La expresión de abajo se refiere a la suma de toda la vida conjunta de todos los componentes que componen el sistema. Es decir que entre más alfas hayan menor es el tiempo de vida esperado.
##### "M está exponencialmente distribuida con parámetro α1 + α2 + . . . + αN y valor  medio 1/(α1 + α2 + . . . + αN)."

#### ¿Cuál es la probabilidad de que cuando el primer fallo se dé, sea el componente
j-ésimo?
##### La probabilidad de que entre las N variables aleatorias Ti el mínimo sea Tj está dada
por la expresión P(Tj = min{T1, T2, . . . , TN}) = αj α1+α2+···+αN

### El proceso de nacimiento y muerte de las cadenas de Marcov
Es una analogía, que se puede interpretar como unión y separación. Nos intereza saber cuanto tiempo dura un elemento en cualquier estado durante un tiepo determinado. El estado de la maquina esta  dado por X0 que para un tiempo particular se encuentra en ese estado.











