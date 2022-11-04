---
title: "Semanas 3-4. Recopilar información sobre redes neuronales y motores"
last_modified_at: 2022-11-03
categories:
  - Blog
---
## Semana 3

En estas semanas he buscado información acerca de estimación de la posición, en relación con la postura humana. (pose estimation). He buscado acerca de eso ya que será útil para explicar la analítica sobre las redes neuronales. De entre todas las estudiadas, finalmente elegiré una de ellas para hacer la comparativa con los movimientos del exoesqueleto. 
También he buscado información sobre el Google Coral. 

He encontrado que hay tres enfoques distintos para modelar el cuerpo humano:

* Skeleton-based model
* Contour based model
* Volume-based model

El que más nos interesa es el primero, ya que lo único no nos interesa saber la posición de las articulaciones de una forma lo más exacta posible. El volumen y el contorno no nos son especialmente útiles para nuestro propósito.

## Semana 4

Le he dedicado unos días a buscar información sobre los distintos motores que se pueden usar y sus ventajas y desventajas.
Si el propósito del exoesqueleto no es levantar mucho peso, como es nuestro caso, entonces los motores que más conviene utilizar son los eléctricos.
En años recientes el control pneumático para/de los robots en rehabilitación se introdujo y se consideró ventajoso en comparación con motores eléctricos debido al factor coste y mayor relación potencia-peso.
Como ya se ha mencionado antes, si nuestro principal objetivo es levantar peso (o se va a necesitar levantar peso) lo mejor es usar actuadores hidráulicos. Sin embargo, necesitan mucha energía de la fuente de alimentación.
Los actuadores pneumáticos son seleccionados normalmente por su peso ligero. El uso de motores hidráulicos y pneumáticos hace que los exoesqueletos no sean portátiles, sean pesados y difíciles de manipular.
Los actuadores eléctricos tienen una alta capacidad de potencia, relación par-peso y precisión. Normalmente son más silenciosos que los hidráulicos y los pneumáticos.
El feedback y el tiempo de respuesta de estos motores (los eléctricos) suele ser corto. Estos motores no son los óptimos si loque se busca es que el movimiento es rápido, sin embargo, como nuestro objetivo esque el exoesqueleto pueda bajar y subir con el paciente dentro, la velocidad no es un requisito indispensable.
Lo que los motores eléctricos proporcionan también es mucha precisión, lo quesí es importante en nuestro proyecto.
