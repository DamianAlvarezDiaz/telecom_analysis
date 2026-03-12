# Proyecto de Bootcamp sobre Telecomunicaciones

## Ejercicio sobre una empresa de telefonía que opera en México y Colombia.
Entregar un reporte para entender cómo los clientes usan realmente los servicios móviles (llamadas y mensajes).

El objetivo de la empresa es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

## Datasets Utilizados

Se emplearon tres fuentes de datos:

plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

## Objetivos particulares

La idea general fue explorar, limpiar y analizar estas bases de datos para construir una visión clara, confiable y accionable sobre el comportamiento de uso de los clientes y cómo varía entre diferentes grupos de usuarios.

💡 Preguntas del negocio
- ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
- ¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro?
- ¿Cómo varía el uso según la edad y el tipo de plan contratado?
- ¿Qué patrones pueden ayudar a diseñar mejores planes, optimizar la oferta y mejorar la satisfacción del cliente?

## 🛠️ Herramientas de la lección
Jupyter Notebook
Python: pandas, numpy, seaborn, matplotlib
Datasets del Proyecto

##  Flujo general del proyecto

1. Cargar y explorar plans, users_latam, usage.	
2. Identificación de problemas de calidad (contar nulos, detectar sentinels, revisar fechas fuera de rango).
3. Limpieza básica (reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas).
4. Summary statistics	(revisar las medidas clave en variables categóricas y numéricas: media, mediana, percentiles).
5. Visualización & outliers	(creación de histogramas y boxplots).
6. Segmentación	(crear segmentaciones basadas en reglas claras; visualizar proporciones con countplots).
7. Insight ejecutivo	(redactar conclusiones y recomendaciones comerciales basadas en los pasos anteriores).


## Cómo ejecutarlo
Ver liga a Google Colab: https://colab.research.google.com/drive/1tTEfEiLjwcS7cOJdT0C_6JNgskeNxtjF

