Nuestro trabajo de texto ha querido tratar sobre un posible caso de uso para NLP sobre extracción de información relevante sobre tweets.

En un primer modelo, se utilizan una serie de topicos arbitrarios con los que se etiquetan unos tweets reales con el objetive de diseñar un modelo que dado un determinado tweet sea capaz de clasificar dicho tweet en uno de los topicos con los que mas puede coincidir en lo referente al contenido. 

Por otro lado, se han desarrollado una serie de modelos (concretamente 3) enfocados en el análisis de sentimientos, que da lugar a una clasificación binaria de los tweets (Positivo:1 , Negativo:0). 

Mencionar que los sets de datos empleados para el entrenamiento han sido diferentes para cada caso, aunque la inferencia y la utilización posterior de los modelos se podrá hacer con los mismos tweets. 

En conclusión, la idea de futuro sería crear un pipeline mediante el cual se puedan extraer tweets de la API de Twitter y automaticamente fueran clasificados tanto por tópico como por sentimiento ya sea positivo o negativo. 

