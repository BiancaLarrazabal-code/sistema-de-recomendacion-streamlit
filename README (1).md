# **Sistema de Recomendación de Productos**

Este proyecto es un sistema de recomendación de productos basado en la similitud de características. Utiliza un algoritmo de **filtrado basado en contenido** para sugerir productos a los usuarios que son similares a uno que ya han seleccionado.

La aplicación está construida con **Python** y **Streamlit**, lo que permite una interfaz web interactiva que muestra las recomendaciones y visualizaciones de datos en tiempo real.

## **Aplicación en el Marketing**

Este sistema va más allá de un simple análisis de datos. Puede ser una herramienta de marketing poderosa, ayudando a:

* **Aumentar la Venta Cruzada**: Recomendar productos complementarios a los clientes basándose en sus intereses, impulsando las ventas.  
* **Mejorar la Experiencia del Cliente**: Ofrecer sugerencias personalizadas y relevantes, lo que aumenta la satisfacción y la lealtad.  
* **Segmentación del Mercado**: Identificar grupos de productos con características similares para campañas de marketing dirigidas.

## **Características**

* **Lógica de Recomendación**: Utiliza la similitud del coseno (cosine\_similarity) para encontrar productos similares basándose en características numéricas.  
* **Visualización Interactiva**: Muestra un gráfico de barras que ilustra la puntuación de similitud de los productos recomendados.  
* **Exportación de Datos**: Guarda las recomendaciones finales en un archivo CSV para su posterior análisis.

## **Tecnologías Utilizadas**

* **Python**  
* **Streamlit** (para la interfaz web)  
* **Pandas** (para la manipulación de datos)  
* **Numpy** (para cálculos numéricos)  
* **Scikit-learn** (para la similitud del coseno)  
* **Matplotlib** (para la visualización de gráficos)

## **Cómo Ejecutar la Aplicación**

Para ejecutar esta aplicación en tu entorno local, sigue estos pasos:

1. **Clona el repositorio**:  
   git clone \[https://github.com/tu\_usuario/sistema-de-recomendacion-streamlit.git\](https://github.com/tu\_usuario/sistema-de-recomendacion-streamlit.git)  
   cd sistema-de-recomendacion-streamlit

2. **Instala las dependencias**:  
   pip install \-r requirements.txt

3. **Ejecuta la aplicación**:  
   streamlit run app.py

La aplicación se abrirá automáticamente en tu navegador web.