Práctico 3: Aprendizaje Supervisado

Introducción:
En la siguiente notebook se presentarán las consignas para desarrollar el tercer práctico de la mentoría, correspondiente a Introducción al Aprendizaje Automático. El objetivo consiste en explorar y aplicar diferentes métodos aprendidos en el curso, y sumar el trabajo realizado en los prácticos 1 y 2 (principalmente estadistica descriptiva y curación del dataset). Nos centraremos principalmente en implementar técnicas y estrategias usuales al momento enfrentar problemas comunes en la vida diaria de un Científico de datos más que en los resultados de los modelos por el momento.

Objetivos:
En dataset disponible, cuentan con los mismos clientes que han generado un Alta de Prestamo (y que hemos analizado) y la misma cantidad de clientes que no han generado un Alta de Prestamo.

Intentaremos responder a la siguiente pregunta:

¿Cuáles son las variables significativas de los clientes bancor que ustedes tendían en cuenta a la hora de invertir en una campaña de marketing de venta de Préstamos Personales?

Para ello se solicita a continuación:

1. Dividir el dataset en conjuntos de entrenamiento, validación y test realizando un muestreo estratificado. ¿Qué variables condiseran relevantes para realizar el muestreo? ¿Por qué?
2. ¿Son las distribuciones de los datos similares en ambos conjuntos? Si la respuesta es no, ¿qué decisión tomarían?
3. Probar un modelo de regresión logística sobre los datos sin normalizar. Para ello realizar la codificación de las variables categóricas elegidas para el modelo, mediante la creación de varibles dummy. Analizar los resultados.
4. Probar un modelo de árboles de decisión también sobre los datos. Se pueden normalizar variables, y evaluar resultados.
5. Analizar y exponer los resultados obtenidos hasta el momento de alguna manera que se puedan comparar entre ellos y elegir el modelo mas performante

Para un mayor enriquecimiento del trabajo práctico, se puede crear nuevos features relacionando las varaibles del dataset, utilizar un distintos criterios de normalización de variables (logaritmo, raiz cuadrada, etc), utilizar distintos métodos de seleccion de variables (regresion forward, regresion backward, regresion stepwise)


Entregas:

1. Breve informe (no más de 2 o 3 páginas) en el cual se explique qué detectaron en el set de datos, qué interpretación le dieron, alternativas de solución y propuesta.
2. El dataset con los cambios implementados en cuanto a curación y normalización.

