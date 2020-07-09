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
Va representar un tiempo de vida la distribución exponencial representa esto.

Si T es el tiempo de vida de un componente que está exponencialmente distribuido con
parámetro α, entonces T tiene densidad
fT (t) = (
0 t < 0
αexp(−αt=)
t > 0
(2)
La media de T es el recíproco del parámetro α, E[T] = 1/α
.
• La variable aleatoria T tiene la propiedad de envejecimiento o de falta de memoria
• “No importa lo viejo que el componente es, este opera como si fuera nuevo”







