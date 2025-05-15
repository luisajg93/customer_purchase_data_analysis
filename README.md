# customer_purchase_data_analysis
Análisis de datos del comportamiento de compra de clientes en la plataforma de comercio electrónico Instacart. ***Proyecto desarrollado como evaluación final del Sprint de Manipulación de Datos con Python del Bootcamp de Data Scientist de TripleTen.***

## Contexto del proyecto
Instacart es una plataforma de entregas de comestibles donde la clientela puede registrar un pedido y hacer que se lo entreguen, similar a Uber Eats y Door Dash.
El conjunto de datos que te hemos proporcionado tiene modificaciones del original. Redujimos el tamaño del conjunto para que tus cálculos se hicieran más rápido e introdujimos valores ausentes y duplicados. Tuvimos cuidado de conservar las distribuciones de los datos originales cuando hicimos los cambios.

Debes completar tres pasos. Para cada uno de ellos, escribe una breve introducción que refleje con claridad cómo pretendes resolver cada paso, y escribe párrafos explicatorios que justifiquen tus decisiones al tiempo que avanzas en tu solución.  También escribe una conclusión que resuma tus hallazgos y elecciones.

## Objetivo del proyecto
Realizar un ánalisis del comportamiento de los clientes en la plataforma dividido en tres etapas. 

## Librerías principales utilizadas
- pandas
- matplotlib

## Principales métodos y técnicas utilizadas
- Análisis exploratorio inicial
- Análisis de datos ausentes y duplicados
- Análisis de distribución de compras
- Agrupación de datos
- Fusión de dataframes
- Filtrado avanzado de datos
- Creación e interpretación de gráficos avanzados

## Resultados
- La mayor cantidad de pedidos se realiza entre las 9:00 y las 16:00. Las 10:00 am y 11:00 am son las horas con mayores pedidos.
- La mayor cantidad de pedidos se realiza los domingos y lunes y los clientes esperan 7 o 30 días para volver a comprar.
- La mayoría de los pedido contiene entre 4 y 7 artículos
- Los pedidos realizados en sábados aumentan entre las 11:00 y 14:00, horas donde desciende la actividad en miércoles.
- Los productos más populares, más resurtidos y más veces agregados como primeros articulos al carrito, son productos alimenticios como frutas, verduras y bebidas, principalmente leches. 
    - En todos los casos, las bananas ocupan el primer lugar
- El user_id 103634 es el usuario que más productos ha comprado (se merece una promoción especial)
- El ordenamiento de datos y las gráficas permiten encontrar comportamientos de los datos para tomar mejores decisiones.