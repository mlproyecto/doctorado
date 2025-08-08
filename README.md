# Mapping Review: Inteligencia Artificial y Machine Learning en Educación Matemática K-12

## Descripción del Proyecto

Este repositorio contiene una revisión sistemática de mapeo (mapping review) sobre las aplicaciones de Inteligencia Artificial (IA) y Machine Learning (ML) en el proceso de enseñanza-aprendizaje de las matemáticas en educación K-12.

## Objetivo

Identificar y analizar las aplicaciones de la Inteligencia Artificial (IA) y Machine Learning (ML) en el proceso de enseñanza-aprendizaje de las matemáticas a través de una revisión sistemática de la literatura.

## Preguntas de Investigación (Mapping Questions - MQ)

- **MQ1**: ¿Cuántos estudios se han publicado a lo largo de los años?
- **MQ2**: ¿Quiénes son los autores más activos del área?
- **MQ3**: ¿Qué tipo de artículos se publican?
- **MQ4**: ¿En qué fuentes aparecen este tipo de estudios?
- **MQ5**: ¿Cuáles son las bases de datos más comunes utilizadas en este tipo de estudios?
- **MQ6**: ¿Qué términos de búsqueda se utilizan para definir la cadena de búsqueda en este tipo de estudios?
- **MQ7**: ¿En qué dominios se centran los estudios?
- **MQ8**: ¿Qué años cubren los estudios de revisión y mapeo?
- **MQ9**: ¿Qué tipo de revisiones se publican?

## Estructura del Repositorio

```
├── README.md
├── MappingReview.csv          # Base de datos principal
├── notebooks/                 # Notebooks de análisis
│   ├── 01_analisis_descriptivo.ipynb
│   ├── 02_autores_activos.ipynb
│   ├── 03_tipos_articulos.ipynb
│   ├── 04_fuentes_publicacion.ipynb
│   ├── 05_bases_datos.ipynb
│   ├── 06_terminos_busqueda.ipynb
│   ├── 07_dominios_estudios.ipynb
│   ├── 08_anos_cobertura.ipynb
│   └── 09_tipos_revisiones.ipynb
├── results/                   # Resultados y visualizaciones
│   ├── figures/
│   └── tables/
└── requirements.txt           # Dependencias de Python
```

## Dataset

El archivo `MappingReview.csv` contiene 126 publicaciones científicas relacionadas con IA y ML en educación matemática K-12, con los siguientes campos:

- **Title**: Título del artículo
- **Author(s)**: Autores
- **Year**: Año de publicación
- **Publication Title**: Título de la revista/conferencia
- **Type of Publication**: Tipo de publicación
- **Source**: Fuente de datos
- **DOI**: Identificador digital del objeto
- **Present in Eric**: Presencia en base de datos Eric
- **Present in IEEE**: Presencia en base de datos IEEE
- **Present in Scopus**: Presencia en base de datos Scopus
- **Present in WoS**: Presencia en base de datos Web of Science
- **Abstract**: Resumen del artículo

## Análisis Realizado

El análisis se realiza utilizando Google Colab con los siguientes notebooks:

1. **Análisis Descriptivo**: Estadísticas generales del corpus
2. **Autores Más Activos**: Identificación de investigadores principales
3. **Tipos de Artículos**: Clasificación por tipo de publicación
4. **Fuentes de Publicación**: Análisis de revistas y conferencias
5. **Bases de Datos**: Uso de diferentes bases de datos
6. **Términos de Búsqueda**: Palabras clave utilizadas
7. **Dominios de Estudio**: Áreas temáticas específicas
8. **Años de Cobertura**: Distribución temporal
9. **Tipos de Revisiones**: Clasificación de revisiones

## Tecnologías Utilizadas

- **Python**: Análisis de datos
- **Pandas**: Manipulación de datos
- **Matplotlib/Seaborn**: Visualizaciones
- **Google Colab**: Entorno de desarrollo
- **GitHub**: Control de versiones

## Cómo Usar

1. Clona este repositorio
2. Abre los notebooks en Google Colab
3. Ejecuta el análisis paso a paso
4. Revisa los resultados en la carpeta `results/`

## Contribuciones

Este proyecto es parte de una investigación doctoral sobre IA en educación matemática.

## Licencia

Este proyecto está bajo la Licencia MIT.

## Contacto

Para más información sobre este proyecto, contacta al autor principal.
