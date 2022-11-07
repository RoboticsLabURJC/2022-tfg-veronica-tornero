---
title: "Semanas 3-4. Recopilar información sobre redes neuronales y motores"
last_modified_at: 2022-11-03
categories:
  - Blog
---

## Semana 5

Los 4 mejores algoritmos de la estimación de la pose teniendo en cuenta nuestro objetivo son:
•	BlazePose
•	MoveNet
•	PoseNet
•	OpenPose
Según el artículo Comparing the Quality of Human Pose Estimation with BlazePose or OpenPose, el algoritmo BlazePose tiene más puntos clave en las manos y en la cara, sin embargo, a nosotros no nos hace falta tener muchos puntos clave en las extremidades; nos basta con saber su posición más o menos exacta. Al no necesitar tantos puntos clave, es una cualidad del BlazePose que no nos afecta ni de manera positiva ni negativa, por lo que no nos beneficia mucho.
Por otro lado, se ha demostrado (encontrado en este mismo artículo), que OpenPose tiene menos tasa de error que este otro algoritmo mencionado anteriormente. La tasa de error es realmente importante ya que es vitar localizar de manera precisa la localización de las extremidades y otras zonas para poder una trayectoria clara. En este caso, OpenPose presenta una gran ventaja. 
Según la información de este artículo, para la tarea que se va a realizar con la red neuronal, BlazePose está bien, pero hay otros algoritmos que lo superan, por lo que queda descartado. Los tres algoritmos “finalistas” son OpenPose, PoseNet y MoveNet.
He encontrado un artículo llamado Comparative Analysis of OpenPose, PoseNet, and MoveNet Models for Pose Estimation in Mobile Devices, donde hace una comparación entre los tres algortimos, OpenPose, PoseNet y MoveNet.
Según el artículo, los tres algoritmos son muy eficientes y poseen cualidades que los hacen los mejores en distintas áreas. En nuestro caso, creo que el algoritmo que mejor se ajusta a nuestras necesidades dado nuestro objetivo, que es saber la posición de las extremidades y diversos puntos clave en el tronco para poder ver la trayectoria que sigue la persona al hacer las sentadillas, es PoseNet. 
Está demostrado que MoveLightning es el modelo más rápido y que OpenPose es el mejor para detectar múltiples personas. Sin embargo, esas cualidades no son tan imprescindibles en nuestro caso como la precisión, y el algoritmo más preciso es PoseNet.
