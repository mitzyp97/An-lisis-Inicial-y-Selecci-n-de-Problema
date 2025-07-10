# An-lisis-Inicial-y-Selecci-n-de-Problema
## Descripción del Proyecto

Este proyecto tiene como objetivo realizar un análisis exploratorio inicial (EDA) de distintos conjuntos de datos de diversas temáticas, con el fin de identificar características, desafíos y patrones relevantes. A partir de este análisis, se selecciona uno de los datasets para definir un problema específico de machine learning (regresión, clasificación o clustering) con una justificación clara.

## Conjuntos de Datos Analizados

1. **Heart Disease Dataset**  
   Dataset clínico con variables fisiológicas y diagnósticas que permiten predecir la presencia o ausencia de enfermedad cardíaca.

2. **Video Game Sales Dataset**  
   Contiene información sobre ventas globales de videojuegos, incluyendo plataforma, género, año y ventas por región.

3. **Netflix Shows Dataset**  
   Datos sobre series y películas en una plataforma de streaming: título, tipo, país, director, clasificación y duración.

4. **Retail Transactions Dataset**  
   Datos de transacciones comerciales, incluyendo edad del cliente, género, categoría de producto, cantidad y monto de compra.

## Resumen del EDA Inicial

- Se identificaron valores faltantes y outliers en varios datasets, particularmente en variables como colesterol, duración, precio y monto total.
- Se aplicaron gráficos como histogramas, boxplots y pie charts para entender mejor las distribuciones y proporciones.
- Algunos datasets presentaron variables altamente correlacionadas, y otros carecían de variables numéricas suficientes para análisis cuantitativo.
- Se documentaron los principales desafíos de calidad de datos, balance de clases y estructuras desiguales entre categorías.

## Problema Seleccionado

**Dataset elegido:** *Heart Disease Dataset*  
**Tipo de problema:** Clasificación  
**Objetivo:** Predecir si un paciente tiene enfermedad cardíaca (0 = No, 1 = Sí) a partir de variables clínicas y demográficas.

### Justificación:
- Tiene una variable objetivo bien definida y balanceada (~55% de casos positivos).
- Las variables predictoras incluyen tanto datos numéricos como categóricos, lo que lo hace apto para modelos supervisados con preprocesamiento mixto.
- Es un problema clínicamente relevante con impacto en la toma de decisiones médicas.
- Representa un desafío técnico interesante, incluyendo detección de outliers y selección de variables relevantes.

## Instrucciones para Ejecutar

1. Clona o descarga este repositorio.
2. Abre los notebooks de análisis (`EDA_1.ipynb`, `EDA_2.ipynb`, etc.) en Google Colab o Jupyter Notebook.
3. Asegúrate de tener instaladas las siguientes librerías:
   - `pandas`, `matplotlib`, `seaborn`, `plotly`
4. Ejecuta las celdas en orden para reproducir los análisis.
5. Revisa el notebook final para ver la selección del problema y posibles modelos aplicables.

## 👥 Autor Mitzy Ponce
