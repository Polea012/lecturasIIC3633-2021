# Lectura 5
## Combining predictions for accurate recommender systems
### Sistemas Recomendadores Pablo Olea - 1663697J

La lectura de esta semana se concentra en el proceso de combinar sistemas recomendadores para mejorar los resultados a base de un experimento. 
En particular se detalla los diferentes sistemas que se combinan por medio de una combinacion lineal
de sus resultados para entregar una recomendacion final.

Es bastante interesante ver que los resultados mejoran al combinar sistemas. Puede parecer intuitivo, sin embargo, uno podría pensar que dado un grupo de modelos es mas sencillo tomar el que de el mejor resultado como herramienta de recomendación. Sin embargo, el documento da a entender que definiendo una cantidad de pesos para cada modelo en conjunto de sus resultados se puede estimar un concenso respecto de las recomendaciones entregada de forma individual. Se podría dar a pensar que aquella recomendación compartida por distintos modelos (calibrado por el nivel de cada uno) dará una respuesta con mayor certeza.

Encontré como un gran aporte el que no únicamente se mostrara la lógica detrás del blending, sino que por medio del ejemplo de la competencia de Netflix se mostraran resultados reales respecto de la metodología. Esto principalmente dado que se ocuparon muchos modelos con parametrizaciones, de manera que observar los resultados ayuda a entender la eficiencia de la técnica. Dicho lo anterior, habría sido igual de interesante ver posibles problemas de usar esta metodología. Se explica inicialmente que el tamaño del proceso y tiempo es costoso, pero como una extensión de este documento se podría evaluar la posibilidad de que se pierda alguna información o se basan ciertos supuestos en este sistema para llegar a buenos resultados.

Los resultados y las explicaciones entregadas generan la pregunta de si efectivamente esta técnica es siempre la mejor, o si existen casos donde hay modelos que generan mejores resultados dado el contexto de la recomendación (mayor peso por parte del modelo), En caso de que efectivamente este método siempre es mejor respecto de un modelo individual, una justificación respecto de ello sería muy interesante.

