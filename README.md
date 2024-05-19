# Regresión Linear

El análisis de regresión es una de las herramientras más importantes en el campo de la estadística, la ciencia de datos y el machine learning.

La regresión busca analizar la relación entre variables y como una variable o varias variables independientes afectan a una variable independiente. Por ejemplo, como la edad, el nivel educativo y la cantidad de años experiencia laboral influyen en los ingresos.

En el caso de este método, la variable dependiente siempre debe ser de tipo cuantitativa. Si la variable que buscamos explicar es de otro tipo, el método de análisis deberá ser otro.

Las variable dependiente también se denomina outputs o response y se simboliza con "y", mientras que las variables independientes también se denominan inputs o regressors y se simbolizan con "x".

La regresión lineal la utilizamos para analizar como y cuanto un fenómeno afecta o influencia a otro. En el ejemplo previo, con que magnitud el nivel educativo afecta a los ingresos. Pero también la utilizamos para predecir valores de la varibale dependiente a partir de nuevos valores de la independiente. Por ejemplo, cuantas camas de internación necesitara un hospital en las semanas próximas en una situación epidémica.

La fórmula con que se presenta la regresión lineal es 
    
    Y=β0+β1X

Donde β0 y β1 son los coeficientes y X e Y son variables. β0 representa el valor de la intercepción de la recta con el eje Y, mientras que β1 representa cuanto crece Y cada vez que X aumenta en 1. Ambos coeficientes se estiman minimizando la suma de los cuadrados de los errores (diferencias entre los valores observados y los predichos), método que se denomina de mínimos cuadrados ordinarios. 

Para saber que tan bien funciona este modelo, debemos saber interpretar el coeficiente de determinación o 𝑅², que determina cuanto del cambio en Y se explica por el cambio en X. Este coeficiente varía entre 0, ningun cambio en Y se explica por cambios en X, y 1, el 100% de los cambios en Y se explican por los cambios en X.

La siguiente imagen ilustra los componentes de un modelo de regresión lineal simple.

![Imagen de ejemplo de regresión lineal simple](reg_linear_1.avif)

En el archivo jupyter que se encuentra en este repositorio se muestra con un ejemplo muy sencillo como utilizar Numpy y ScikitLearn para crear un modelo de regresión lineal simple.