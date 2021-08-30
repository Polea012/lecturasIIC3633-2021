# Lectura 2
## Matrix Factorization
### Sistemas Recomendadores Pablo Olea - 1663697J

La lectura de esta semana se concentra en _Matrix factorization_, una estrategia de _collaborative filtering_ los sistemas recomendadores, además de explicar diferentes técnicas para mejorar su rendimiento.

Encontré particularmente interesante el problema del _bias_ y la solución que se presenta. Uno de los aspectos críticos de los grandes conjuntos de datos es que no todos son iguales en su contexto (los usuarios pueden ser mas estrictos que otros respecto de sus puntajes o hay películas que tienen una tendencia a recibir puntajes específicos). Llama la atención que la solución propuesta en esencia busca ponderar estos casos para que no alteren de manera significativa o disociativa a los resultados finales.

Respecto de lo anterior, me llama la atención si esta solución se ve afectada por _review bombing_ (exceso de críticas negativas o positivas a propósito) dado que asume que los patrones de una película están dados exclusivamente por los puntajes recibidos por los usuarios. Puede ser que una película recibe alta puntuaciones por su popularidad, pero no por su calidad.

Se da a entender que incluso el aspecto de _bias_ no puede resolverse de manera directa ya que existen grados de dinamismo al momento de analizar todos los datos. Me pareció acertado que el documento se refiriera a los casos donde las percepciones de un usuario pueden cambiar con el tiempo, al igual que las películas, e incluso aprovechan esta complejidad para captar patrones y mejorar aún mas su solución.

El éxito alcanzado en la competencia de Netflix da a entender que inicialmente las técnicas, si bien poistivas, no tenían un nivel alto de eficiencia hasta que se masificó el interés por los sistemas recomendadores. Habría sido interesante sin embargo que se explicara en forma detallada cuales fueron las variantes aplicadas sobre las ecuaciones de la matriz que les permitieron alcanzar un _performance_ tan alto para ganar (el cual después mejoraron hasta casi la perfección). Si bien mencionan algunas estrategias, podrían haber mostrado la aplicación de ellas en aspecto técnico.