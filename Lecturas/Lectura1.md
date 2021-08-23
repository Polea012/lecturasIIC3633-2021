# Lectura 1
## Collaborative Filtering
### Sistemas Recomendadores Pablo Olea - 1663697J

La lectura de esta semana se concentra en _Collaborative  Filtering_, una estrategia de los sistemas recomendadores para predecir y proporcionar intereses a un usuario sobre alguna temática a partir de información recolectada de las preferencias de una gran cantidad de usuarios.

El documento detalla las diferentes formas de abordar CF considerando los beneficios y complicaciones que cada una puede tener, explicando que en general no hay una metodología concreta para construir un sistema sin depender de la naturaleza de los datos junto con su volumen. En este aspecto se explica como es que los algoritmos probabilísticos tienden atener mejores resultados dado que se basan en agrupar los datos en sus contextos.

Una lectura bastante completa, en particular es bastante interesante como es que equilibra los factores técnicos (como se construye el programa del sistema recomendador, cálculos matemáticos, etc) como los factores externos (dependencias sociales, contexto de los usuarios y el entorno donde se obtienen los ratings, etc).

En la sección final del documento se plantean diversas preguntas respecto de CF. En particular la segunda sección de las preguntas, (ciclo de vida del usuario) plantea el efecto del cambioen puntuaciones antiguas y nuevas y como estas podrían afectar al usuario respecto de sus recomendaciones. En base de eso, se habla si es detectable que un usuario varíe en sus recomendaciones por sus gustos.

En particular seguir de manera individual el comportamiento de un usuario (si cambian sus gustos, si es que sus ratings estaban errados) puede ser muy complejo e incluso de pocautilidad si es que hay un grado de volatilidad en los resultados (un usuario puede que cambie de gustos de manera esporádica, incluso regresando a pensamientos previos) por lo que lossistemas CF se deberían concentrar en ver el flujo de los cambios de ratings en grupos de usuarios con ciertos aspectos en comùn. La lectura misma se refiere a esto para referirse alas recomendaciones, pero se podría expandir para ver los flujos de cambios en el tiempo y si es que hay algún patrón o modalidad definible.