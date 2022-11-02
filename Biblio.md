### INFORMACÍON RECOIDA SOBRE REDES NEURONALES Y GOOGLE CORAL

Se necesita buscar información sobre las disintas redes neuronales que estimen las posturas de las personas.
Según he estado investigando, hay distintos tipos de redes neuronales que se podrían usar, dependiendo del objetivo que se tenga. Empezaré hablando de algunas en general, las que he ido encontrando según navegaba en Internet, y más adelante me centraré en las 3 que más se ajustan a lo que queremos hacer.

En este link hay información sobre las distintas formas(top-down approach y bottom-up approach) de obtener los puntos clave para realizar la detección: mapas de calor y regresíon directa.
https://blog.damavis.com/deteccion-de-poses-humanas-mediante-deep-learning/

En este otra url podemos encontrar información sobre qué es una red neuronal.
https://aws.amazon.com/es/what-is/neural-network/

He encontrado un artículo llamado ***Redes Neuronales: Conceptos Básicos y Aplicaciones*** que es una muy buena fuente de información acerca de redes neuronales. Vienen tipos, distintas aplicaciones, los elementos que las componen, etc.

Este link proporciona una definición de estimación de poses, al igual que también habla sobre dos herramientas para detectar  las expremidads y articulaciones: MoveNet y PoseNet. También hay una comparativa entre los dos sabores distintos de MoveNet.
https://www.tensorflow.org/lite/examples/pose_estimation/overview

En esta otra url hay información sobre otra herramienta también utilizada, llamada *Sift*. Esta forma de hacerlo es menos fiable ya que tiene mucho error. No sé si se puede usar con vídeos también, o si es solo con fotos. Utiliza el gradiente.
https://programmerclick.com/article/1147927769/

Este link es muy importante. En él hay un montón de información, incluidos los distintos algoritmos más comunes que utilizan las redes neuronales para la detección de la pose de las personas. Habla también sobre la *estimación de la pose* y cómo funciona. Incluye ejemplos de vídeo con personas en las que les detecta sus articulaciones.
https://viso.ai/deep-learning/pose-estimation-ultimate-overview/

##### Una breve descripción de cada uno de ellos (obtenida de el link anterior).

* OpenPose:
Es muy robusto y proporciona la capacidad de detectar un total de 135 puntos vitales. Es uno de los mejores modelos. Es lightweight version y utiliza el bottom-up approach.

* High-Resolution Net(HRNet):
Red neuronal para la estimación de las postura humana útil en deportes televisados. Es capaz de mantener representaciones de alta resolución durante el proceso.

* DeepCut:
Es útil para la detección en muchas personas a la vez utilizando la aproximación bottom-up. No dudo en que sea fiable y que sirva de ayuda pero está especializado en detectar muchas personas a la vez y eso no es lo que buscamos.

* AlphaPose:
Es útil para detectar poses en presencia de cajas de delimitación inexactas. Se puede usar para la detección de múltiples personas o de una sola.

* DeepPose:
Aprovecha el uso de las redes neuronales profundas. Captura todas las articulaciones.

* PoseNet:
Hecho en tensorflow.js para que funcione en dispositivos ligeros como cóviles. Se puede usar para detectar una o varias personas.

* DensePose:
Intenta mapear todos los píxeles del ser humano (de la persona a analizar).

* TensorFlow Pose Estimation.
