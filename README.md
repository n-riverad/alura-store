# AluraStoreLatam

## Propósito del análisis

Este proyecto tiene como objetivo analizar los datos de ventas de AluraStore, una tienda online, con el fin de extraer insights clave sobre el comportamiento de los clientes, los productos más vendidos y el rendimiento de las estrategias de marketing. Se busca responder preguntas como:

- ¿Cuáles son los productos más populares?
- ¿Cómo se comportan las ventas a lo largo del tiempo?
- ¿Qué factores influyen en el ticket promedio?
- ¿Qué segmentos de clientes son más rentables?

El análisis fue desarrollado dentro del contexto de un curso de Alura Latam para aplicar habilidades en Python, análisis exploratorio y visualización de datos.


## Ejemplos de gráficos e insights

Durante el análisis se generaron múltiples visualizaciones con seaborn y matplotlib, tales como:

- Gráfico de barras de los productos más vendidos
- Series de tiempo del total de ventas por mes
- Gráficos de dispersión para analizar el ticket promedio según categorías
- Mapas de calor para analizar correlaciones entre variables

### Ejemplos de insights:

- Los productos de la categoría "Electrónicos" presentan el mayor ticket de venta, pero no el mayor volumen.
- La calificación promedio de las tiendas es de ~4.0
- Las tiendas mantienen un ticket promedio de envío constante.

## Instrucciones para ejecutar el notebook

1. Abre el siguiente enlace para acceder a Google Colab: https://colab.research.google.com/
2. Haz clic en "Archivo" > "Subir notebook" y selecciona `AluraStoreLatam.ipynb`.
3. Asegúrate de ejecutar la primera celda para importar los archivos CSV correspondientes (clientes, productos, pedidos, transacciones).
4. Ejecuta cada celda del notebook desde el entorno Colab.

## Requisitos

Google Colab ya incluye por defecto las bibliotecas necesarias. En caso de que necesites instalarlas manualmente, puedes usar:

```python
!pip install pandas matplotlib seaborn
```

