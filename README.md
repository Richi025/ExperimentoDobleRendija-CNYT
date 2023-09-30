# ExperimentoDobleRendija-CNYT

Este repositorio contendrá un experimento sobre el fenómeno de la doble rendija y su correspondiente explicación fundamentada en los principios de la computación cuántica.

# OBJETIVO

El propósito fundamental de este experimento es investigar y comprender el modo en que las partículas, en particular los electrones, se comportan en ciertas condiciones y entornos específicos. Se busca profundizar en el conocimiento de cómo estas partículas, que conforman la base de la materia, interactúan y se distribuyen cuando se enfrentan a una situación particular, como la presencia de dos rendijas en una barrera. A través de este estudio, se aspira a desentrañar los misterios de la física cuántica y obtener una visión más completa y precisa del comportamiento de las partículas subatómicas en el mundo de la física, lo que puede tener implicaciones significativas en nuestro entendimiento de la naturaleza misma del universo.

# EXPLICACION DEL EXPERIMENTO
En el experimento, utilizamos un láser que emite un haz de electrones hacia una placa de papel de aluminio con dos rendijas. Cada electrón en este haz tiene una igual probabilidad de pasar por una de las dos rendijas, pero no puede atravesar ambas al mismo tiempo. En un escenario intuitivo, podríamos esperar que los electrones pasen por una rendija y luego se reflejen en la pared formando acumulaciones de partículas, es decir, "pepas", frente a cada rendija, creando dos grupos separados en la pared, uno a la derecha y otro a la izquierda.

Sin embargo, cuando examinamos los resultados reales del experimento, nos damos cuenta de que esto no sucede como cabría esperar. ¿Por qué no ocurre así, a pesar de ser una explicación lógica?

Una posible explicación sería que los electrones, después de pasar por la rendija, no siguen una trayectoria recta y pueden cambiar de dirección, lo que significa que podrían impactar en cualquier lugar de la pared. Esto solo sería posible si algo o alguien afectara su trayectoria, ya que, según la naturaleza del experimento, los electrones deberían mantener su dirección original.

Es en este punto donde la física cuántica entra en juego para explicar este fenómeno. Actualmente, la teoría más aceptada en la comunidad científica es que un "elemento" o "objeto" ajeno a la partícula en sí misma, es decir, una entidad perteneciente a un universo distinto, está afectando la trayectoria del electrón y haciendo que cambie de dirección. Esta otra historia o versión de la partícula, proveniente de otro universo, influye en la trayectoria de nuestra partícula original, generando una distribución uniforme de "pepas" en la pared, que se ve más como una línea de partículas.

Esta teoría plantea la posibilidad de hablar sobre el multiverso, donde las partículas en nuestro universo tienen versiones alternativas de sí mismas en otros universos, y estas versiones pueden interactuar entre sí, afectando los resultados observados en nuestro universo.

# SIMULACION DEL EXPERIMENTO

Para llevar a cabo las simulaciones, empleamos un enfoque basado en un modelo matemático que se fundamenta en los grafos del sistema y en las matrices de adyacencia que se aplican a estos grafos. Luego, ejecutamos una simulación utilizando una biblioteca específica de Python para manejar números complejos, importando dicha biblioteca desde GitHub. https://github.com/Richi025/Classical_to_Quantum.git

## EXPLICACION E IMAGENES

### Coeficientes Reales.

Doble Rendija con coegicientes reales, los nodos intermedios actúan como rendijas y se tiene la misma resticcion de que al final de cada nodo apunta hacía si mismo suponiendo un ciclo con aristas de valor 1. Para generar un sistema doblemente estocástico.
![realesR](https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/f2a0ebd1-7d8a-4c8b-b4fb-345fa664acd4)

Matiz con coeficientes reales.

![Matriz R](https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/907e7ef7-652f-43fc-ae20-4b1a8a93c7de)

Para este sistema realizaren la matriza y evaluaremos el comprotamiento del sistema con varios Clicks, la fórmula que usaremos para identificar la probabilidad de estar en cierto punto de sistema será p(xj) = |cj|Exp(2).

![reales](https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/0a1dd6b3-115b-4df8-b949-d8728c3ad3be)

Luego de ejecutar el sistema con un click.
Observamos que P(x1) = 0.5 y P(x2)= 0.5.

![result, reales](https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/939c447b-f8b8-4ab9-9a51-4dcb6f46273e)

A continuación se ejecuta el sistema con varios clicks.
Observamos que P(x3) = 1/6, P(x4)= 1/6, P(x5) = 1/3, P(x6)= 1/3, P(x7) = 1/6.

De acuerdo con los resultados P(xj) observamos que luego de varios clicks en el sistema empieza a existir interferencia, ya que los fotones de luz ya no viajan a dos lados unicamente, sino que se dispersan en varios blancos u objetivos del experimento. Esto se debe a la fisica cuantica y la teoria de los multiversos (como parte de la simulación).

![resdutl vvv](https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/1eb56549-e93e-4ad2-90fb-12012e3181ea)

### Coeficientes complejos.

Doble Rendija con coegicientes complejos, es similar al sistema con coeficientes reales, sin embargo los coeficientes complejos nos dan otra perspectiva de la probabilidad del sistema, por tanto usaremos un modelo diferente, el cual mostramos acontinuación.

![diagrama](https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/878a555d-1839-47e0-849c-b1dabf52dedd)

Matiz con coeficientes complejos.

![matriz](https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/7d3d5247-44b5-4248-9c30-83f010ba989f)

Para este sistema realizaren la matriza y evaluaremos el comprotamiento del sistema con varios Clicks, la fórmula que usaremos para identificar la probabilidad de estar en cierto punto de sistema será p(xj) = |Cj|Exp(2)/||y>|Exp(2).

![prueba](https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/ed92e7d9-f841-4081-a8cb-60bc41b5b7c1)


Luego de ejecutar el sistema con un click.
Observamos que P(x1) = 1/sqr(2) y P(x2)= 1/sqr(2) .

![resultSistema](https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/f8cb1e95-1c0a-46f4-856c-899e3cfbacd9)

A continuación se ejecuta el sistema con varios clicks.
Observamos que P(x3) = sqr(6)/6, P(x4)= sqr(6)/6, P(x5) = sqr(6)/3, P(x6)= sqr(6)/6, P(x7) = sqr(6)/6.

De acuerdo con los resultados P(xj) observamos que luego de varios clicks en el sistema empieza a existir interferencia, ya que los fotones de luz ya no viajan a dos lados unicamente, sino que se dispersan en varios blancos u objetivos del experimento. Esto se debe a la fisica cuantica y la teoria de los multiversos (como parte de la simulación).

# ELABORACIÓN

## Materiales:

1. Un Carton Paja.
2. Una cartulina.
3. Un laser.
4. Un bisturi.
5. Un cuarto de papel vinipel.
6. cinta transparente.
7. una caja para soportar el laser.
   
## Procedimiento

1. Cortamos un troso de papel vinipel y lo pegamos con la cinta a un recuadro de cartulina para dar estabilidad.
2. Cortamos el papel vinipel con el visturi creando la doble rendija.
3. Pegamos el recuadro de cartulina con el papel vinipel a la caja.
4. Ubicamos el laser sobre la caja de la manera que apunte a la doble rendija para  reflejar el efecto en el carton paja.

## Imagen del experimento montado.

![WhatsApp Image 2023-09-30 at 1 15 13 PM](https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/0871844b-ee35-4d81-98bb-7f701728344d)

## Video 

https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/ee1df87e-9a1a-46c6-9be2-095f6394374a

## Resultado Final
![WhatsApp Image 2023-09-30 at 1 15 14 PM](https://github.com/Richi025/ExperimentoDobleRendija-CNYT/assets/138072260/a65a63f1-f7fc-4c5f-91c0-443f92e6b327)

# Version

## "Primera Version"

# Autores

1. Alexandra Cortes Tovar.
2. Juan Sebastian Vasquez Vega.
3. Jose Ricardo Vasquez Vega.
