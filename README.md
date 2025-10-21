# Mapping Review: Inteligencia Artificial y Machine Learning en Educación Matemática K-12

## 📋 Descripción del Proyecto

Este repositorio describe el proceso realizado en la **Revisión Sistemática de Literatura (Systematic Review of literature - SLR)** sobre las aplicaciones de Inteligencia Artificial (IA) y Machine Learning (ML) en el proceso de enseñanza-aprendizaje de las matemáticas en educación K-12.

**Dataset**: 89 publicaciones científicas analizadas (2021-2025)

## 🎯 Objetivo

Identificar y analizar sistemáticamente las aplicaciones de la Inteligencia Artificial (IA) y Machine Learning (ML) en el proceso de enseñanza-aprendizaje de las matemáticas a través de una revisión exhaustiva de la literatura científica.

## ❓ Preguntas del mapeo de literatura (Mapping Questions - MQ)

- **MQ1**: ¿Cuántos estudios se han publicado a lo largo de los años?
- **MQ2**: ¿Quiénes son los autores más activos del área?
- **MQ3**: ¿Qué tipo de artículos se publican?
- **MQ4**: ¿En qué fuentes aparecen este tipo de estudios?
- **MQ5**: ¿Cuáles son las bases de datos más comunes utilizadas en este tipo de estudios?
- **MQ6**: ¿Qué términos de búsqueda se utilizan para definir la cadena de búsqueda en este tipo de estudios?
- **MQ7**: ¿En qué dominios se centran los estudios?
- **MQ8**: ¿Qué años cubren los estudios de revisión y mapeo?
- **MQ9**: ¿Qué tipo de revisiones se publican?

## ❓ Preguntas de Investigación (Research Questions - RQ)
- **RQ1**: ¿Cuáles son las aplicaciones de la Inteligencia Artificial y del Machine Learning en procesos de aprendizaje-enseñanza de las matemáticas en la educación media?
- **RQ2**: ¿Qué tipos de metodologías didácticas mediadas con Inteligencia Artificial y Machine Learning son aplicadas en la enseñanza de la matemática en la educación media?
- **MQ3**: ¿Cuáles son los modelos pedagógicos que se usan cuando se implementa Inteligencia Artificial y Machine Learning en la enseñanza de las matemáticas en la educación media?

## 📁 Estructura del Repositorio

```
├── README.md
├── MappingReview.csv          # Base de datos principal (89 publicaciones)
├── requirements.txt           # Dependencias de Python
├── notebooks/                 # Notebooks de análisis
│   ├── 01_analisis_descriptivo.ipynb
│   ├── 02_autores_activos.ipynb
│   ├── 03_tipos_articulos.ipynb
│   ├── 04_fuentes_publicacion.ipynb
│   ├── 05_bases_datos.ipynb   # Notebook para análisis de bases de datos (Google Colab)
│   ├── 05_bases_datos.py      # Script Python para análisis de bases de datos (local)
│   ├── 06_terminos_busqueda.ipynb
│   ├── 07_dominios_estudios.ipynb
│   ├── 08_anos_cobertura.ipynb
│   └── 09_tipos_revisiones.ipynb
└── results/                   # Resultados y visualizaciones
    ├── figures/
    └── tables/
```

## 📊 Dataset

El archivo `MappingReview.csv` contiene **89 publicaciones científicas** relacionadas con IA y ML en educación matemática K-12, con los siguientes campos:

- **Title**: Título del artículo
- **Author(s)**: Autores
- **Year**: Año de publicación
- **Publication Title**: Título de la revista/conferencia
- **Type of Publication**: Tipo de publicación
- **Source**: Fuente de datos
- **DOI**: Identificador digital del objeto
- **Abstract**: Resumen del artículo

## 🔬 Análisis Realizado

El análisis se realiza utilizando **Google Colab** con los siguientes notebooks:

1. **Análisis Descriptivo**: Estadísticas generales del corpus
2. **Autores Más Activos**: Identificación de investigadores principales
3. **Tipos de Artículos**: Clasificación por tipo de publicación
4. **Fuentes de Publicación**: Análisis de revistas y conferencias
5. **Bases de Datos**: Uso de diferentes bases de datos
6. **Términos de Búsqueda**: Palabras clave utilizadas
7. **Dominios de Estudio**: Áreas temáticas específicas
8. **Años de Cobertura**: Distribución temporal
9. **Tipos de Revisiones**: Clasificación de revisiones

## 🛠️ Tecnologías Utilizadas

- **Python**: Análisis de datos
- **Pandas**: Manipulación de datos
- **Matplotlib/Seaborn/Plotly**: Visualizaciones
- **NLTK/TextBlob**: Procesamiento de texto
- **Scikit-learn**: Análisis de machine learning
- **Google Colab**: Entorno de desarrollo

## 🚀 Cómo Usar

### Opción 1: Google Colab (Recomendado)
1. Abre los notebooks en Google Colab
2. Ejecuta el análisis paso a paso
3. Revisa los resultados generados

### Opción 2: Entorno Local
1. Clona este repositorio
2. Instala las dependencias: `pip install -r requirements.txt`
3. Abre los notebooks en Jupyter Lab o VS Code
4. Ejecuta el análisis

## 📈 Resultados Principales

### 📊 Estadísticas Generales
- **Dataset**: 89 publicaciones científicas analizadas (2020-2025)
- **Crecimiento**: Tendencia exponencial con pico en 2024 (35 publicaciones)
- **Autores**: 335 investigadores únicos identificados
- **Promedio**: 4.0 autores por publicación

### 📚 Distribución por Fuentes
- **Scopus**: 44 publicaciones (49.4%) ⭐ Dominante
- **WoS**: 21 publicaciones (23.6%)
- **Eric**: 18 publicaciones (20.2%)
- **IEEE**: 6 publicaciones (6.7%)

### 📄 Tipos de Publicación
- **Artículos**: 52 publicaciones (58.4%) ⭐ Dominante
- **Conferencias**: 33 publicaciones (37.1%)
- **Capítulos de libro**: 4 publicaciones (4.5%)

### 🎯 Dominios de Investigación
- **Educación**: 58 estudios (65.2%) ⭐ Dominante
- **Inteligencia Artificial**: 55 estudios (61.8%)
- **Matemáticas**: 45 estudios (50.6%)
- **Tecnología**: 9 estudios (10.1%)
- **Evaluación**: 7 estudios (7.9%)
- **Personalización**: 7 estudios (7.9%)

### 📋 Trabajos de Revisión Identificados
- **Total**: 4 trabajos específicos (4.5% del total)
- **Tipos**: Systematic Review (3.4%), Mapping/Scoping Review (1.1%), Narrative Review (1.1%)
- **Cobertura**: 2022-2024

### 🔍 Términos Más Frecuentes
- **learning** (52), **mathematics** (30), **based** (18), **school** (17), **students** (16)
- **machine** (15), **education** (14), **intelligence** (13), **artificial** (11), **teachers** (10)

## 📚 Contribuciones

Este trabaja es parte de un **proyecto de investigación** sobre IA/ML en el proceso de enseñanza-aprendizaje de las matemáticas.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.

## 👤 Contacto

Para más información sobre este proyecto, contacta al autor principal al correo: deiviseduard.ramirez@unir.net.

---

**Nota**: Este proyecto está optimizado para ejecutarse en Google Colab para mejor compatibilidad y rendimiento.
