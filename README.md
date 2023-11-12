# Análisis de Sentimientos en Comentarios de Instagram

## Autor
Dijeim Solun Manrique Rodriguez

## Objetivos
El objetivo principal de este proyecto es evaluar la precisión de un modelo basado en NLTK para el análisis de sentimientos en comentarios en español de Instagram. Además, se busca establecer métricas de evaluación para medir la efectividad de este análisis.

## Tecnologías Utilizadas
- Procesamiento de datos: Pandas, PySpark
- Análisis EDA (Exploratory Data Analysis): Pandas, Numpy, Matplotlib, Seaborn
- Lenguaje de Programación: Python
- Entorno de Desarrollo: Google Colab
- Extracción de Datos: Export Comments (https://es.exportcomments.com/)

## Comentario Sobre el Dataset
El dataset utilizado en este proyecto consta de 98 comentarios extraídos de una publicación de Instagram del portal de Radio Programas del Perú (RPP) con fecha 26 de octubre de 2023. La extracción de los datos se realizó utilizando la herramienta en línea disponible en el siguiente enlace: [Export Comments](https://es.exportcomments.com/), y se guardaron en formato CSV.

## Hallazgos Importantes
-Problemas con comentarios ironicos y/o sarcasticos.
-Importancia de precision de modelos abiertos en español.
## Conclusiones del Proyecto
-El uso de modelos pre entrenados para análisis de sentimientos en español tiene un rendimiento deficiente al enfrentarse a comentarios sarcásticos, algo común en la cultura latinoamericana. Se requiere mejorar la capacidad del modelo para interpretar con precisión este tipo de contenido.
-El modelo necesita algunos ajustes para poder enfrentar cualquier tipo de publicación sin complicaciones.
