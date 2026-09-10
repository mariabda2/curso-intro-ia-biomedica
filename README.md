# 🧬 Módulo 6 — Introducción al Análisis de Datos utilizando Herramientas de Inteligencia Artificial

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Colab](https://img.shields.io/badge/Google%20Colab-Notebooks-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![License](https://img.shields.io/badge/Licencia-MIT-2A9D8F?style=for-the-badge)

**Universidad de Antioquia**  


</div>

---

## 🏛️ Información institucional

| Campo | Detalle |
|-------|---------|
| **Institución** | Universidad de Antioquia |
| **Módulo** | 6 — Introducción al Análisis de Datos con IA |
| **Modalidad** | Teórico-práctica · Google Colab |
| **Nivel** | Principiante → Intermedio |
| **Idioma** | Español |

---

## 📖 Descripción

Este repositorio contiene el material didáctico oficial módulo "Introducción al análisis de datos utilizando herramientas de inteligencia artificial". A través de cuatro notebooks de Google Colab, los estudiantes recorren un camino progresivo desde los fundamentos del análisis de datos hasta la construcción de pipelines completos de inteligencia artificial aplicados a problemas clínicos y biomédicos reales.

El módulo está diseñado para profesionales de las ciencias de la salud **sin experiencia previa en programación**, con énfasis en la interpretación clínica de los resultados, la reproducibilidad científica y la ética en el uso de IA en salud.

---

## 🗺️ Estructura del módulo

```
cacbb-modulo6-ia-biomedica/
│
├── 📓 Sesion_01_Intro_Analisis_Datos_IA.ipynb
├── 📓 Sesion_02_IA_Ciencias_Biomedicas.ipynb
├── 📓 Sesion_03_Herramientas_IA_Biomedicas.ipynb
├── 📓 Taller_Final_Analisis_Datos_IA.ipynb
│
└── 📄 README.md
```

---

## 📚 Contenido por sesión

### 🔵 Sesión 01 — Introducción al Análisis de Datos con IA
[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CACBB/cacbb-modulo6-ia-biomedica/blob/main/Sesion_01_Intro_Analisis_Datos_IA.ipynb)

Fundamentos conceptuales y primera experiencia práctica con Python y machine learning.

| Tema | Herramientas |
|------|-------------|
| ¿Qué es la IA y el análisis de datos? | — |
| Ecosistema Python para ciencia de datos | NumPy, Pandas, Matplotlib, Seaborn |
| Análisis exploratorio de datos (EDA) | Pandas, Estadística descriptiva |
| Limpieza y preprocesamiento básico | Pandas, Imputación |
| Primera IA: clustering y clasificación | Scikit-learn (K-Means, Árbol de Decisión) |
| Visualización de resultados | Matplotlib, Seaborn |

**Datasets:** Iris 🌸 · Titanic 🚢

---

### 🟠 Sesión 02 — Aplicación de la IA en las Ciencias Biomédicas
[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CACBB/cacbb-modulo6-ia-biomedica/blob/main/Sesion_02_IA_Ciencias_Biomedicas.ipynb)

Modelos predictivos aplicados a problemas clínicos reales con énfasis en métricas médicas.

| Tema | Herramientas |
|------|-------------|
| Métricas clínicas: sensibilidad, especificidad, ROC-AUC | Scikit-learn |
| Caso 1: Predicción de diabetes | Pima Indians Dataset |
| Caso 2: Clasificación de tumores mamarios | Wisconsin Breast Cancer Dataset |
| Caso 3: Análisis epidemiológico cardiovascular | Framingham Heart Study (simulado) |
| Curvas ROC y matrices de confusión | Matplotlib, Seaborn |
| Ética de la IA en salud | Principios OMS 2021 |

**Datasets:** Pima Indians Diabetes · Wisconsin Breast Cancer · Framingham simulado

---

### 🟣 Sesión 03 — Herramientas de IA en las Ciencias Biomédicas
[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CACBB/cacbb-modulo6-ia-biomedica/blob/main/Sesion_03_Herramientas_IA_Biomedicas.ipynb)

Ecosistema completo de herramientas especializadas para biomedicina e investigación.

| Tema | Herramientas |
|------|-------------|
| Bases de datos biomédicas públicas | NCBI Entrez API, Biopython |
| Análisis de secuencias de ADN (BRCA1) | Biopython |
| Procesamiento de señales ECG | NeuroKit2 |
| Reducción de dimensionalidad en datos ómicos | PCA, t-SNE, UMAP |
| NLP clínico: extracción de entidades | NLTK, WordCloud |
| IA generativa en biomedicina | LLMs médicos (BioGPT, Med-PaLM 2) |
| Pipeline reproducible con buenas prácticas | Scikit-learn Pipeline, GridSearchCV |

**Datos:** PubMed API · Secuencia BRCA1 · ECG sintético · RNA-seq simulado · Notas clínicas

---

### 🏆 Taller Final — Análisis de Datos utilizando IA
[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CACBB/cacbb-modulo6-ia-biomedica/blob/main/Taller_Final_Analisis_Datos_IA.ipynb)

Proyecto integrador de principio a fin con el **Cleveland Heart Disease Dataset**.

| Fase | Contenido | Pts |
|------|-----------|-----|
| 1 | Comprensión del problema clínico | 10 |
| 2 | Análisis exploratorio completo | 20 |
| 3 | Preprocesamiento e ingeniería de características | 15 |
| 4 | Benchmarking y optimización de modelos | 25 |
| 5 | Evaluación clínica (ROC, FN, Curva de Aprendizaje) | 15 |
| 6 | Interpretabilidad global y local + nota clínica | 10 |
| 7 | Informe científico IMRD + declaración ética | 5 |
| BONUS | Ensemble · Análisis de umbral · Sesgo · PCA | +10 |

**Dataset:** Cleveland Heart Disease (UCI ML Repository, 303 pacientes)

---

## 🛠️ Requisitos técnicos

No se requiere instalación local. Todos los notebooks corren directamente en **Google Colab** con una cuenta de Google gratuita.

### Bibliotecas utilizadas

| Categoría | Bibliotecas |
|-----------|-------------|
| **Análisis de datos** | NumPy, Pandas |
| **Visualización** | Matplotlib, Seaborn, WordCloud |
| **Machine Learning** | Scikit-learn |
| **Señales biomédicas** | NeuroKit2, WFDB |
| **Bioinformática** | Biopython |
| **NLP** | NLTK |
| **Reducción de dimensionalidad** | UMAP-learn |

> Todas las bibliotecas se instalan automáticamente en la primera celda de cada notebook.

---

## 🚀 Cómo usar este repositorio

### Opción A — Abrir directamente en Colab *(recomendada)*

1. Haz clic en el botón **"Abrir en Colab"** del notebook que deseas usar.
2. En Colab: **Entorno de ejecución → Ejecutar todo** o ejecuta celda por celda con `Shift + Enter`.
3. Al finalizar: **Archivo → Descargar → .ipynb** para guardar tu trabajo.

### Opción B — Clonar el repositorio

```bash
git clone https://github.com/CACBB/cacbb-modulo6-ia-biomedica.git
cd cacbb-modulo6-ia-biomedica
```

Luego sube el notebook de interés a [colab.research.google.com](https://colab.research.google.com) mediante **Archivo → Subir notebook**.

### Opción C — Desde Google Drive

1. Descarga el `.ipynb` desde este repositorio.
2. Súbelo a tu Google Drive.
3. Ábrelo con Google Colaboratory.

---

## 📋 Ruta de aprendizaje recomendada

```
Sesión 01          Sesión 02            Sesión 03           Taller Final
────────────       ──────────────       ──────────────       ────────────────
Fundamentos   →    Casos clínicos   →   Herramientas     →   Proyecto
Python + EDA       Diagnóstico IA       Especializadas        Integrador
~2-3 horas         ~3 horas             ~3-3.5 horas          ~4+ horas
```

> Se recomienda completar las sesiones en orden antes de abordar el Taller Final.

---

## 🎯 Competencias del módulo

Al completar este módulo, el estudiante será capaz de:

- ✅ Aplicar el ciclo completo de análisis de datos: carga → EDA → limpieza → modelado → evaluación → comunicación.
- ✅ Seleccionar y justificar algoritmos de machine learning apropiados para problemas biomédicos.
- ✅ Interpretar métricas clínicas críticas: sensibilidad, especificidad, ROC-AUC y sus implicaciones diagnósticas.
- ✅ Procesar señales fisiológicas (ECG), secuencias biológicas (ADN) y texto clínico (NLP).
- ✅ Construir pipelines reproducibles siguiendo estándares científicos (TRIPOD+AI).
- ✅ Identificar y mitigar sesgos algorítmicos en modelos de salud.
- ✅ Comunicar hallazgos en formato de informe científico (IMRD).
- ✅ Aplicar principios éticos en el desarrollo y uso de IA en salud (Marco OMS 2021).

---

## 📖 Bibliografía principal

| Recurso | Referencia |
|---------|-----------|
| *Deep Medicine* | Topol, E. (2019). Basic Books. |
| *Hands-On ML with Scikit-Learn, Keras & TensorFlow* | Géron, A. (2022). O'Reilly. |
| *Python Data Science Handbook* | VanderPlas, J. (2016). O'Reilly. Disponible en: https://jakevdp.github.io/PythonDataScienceHandbook |
| *Ethics and governance of AI for health* | OMS (2021). https://www.who.int/publications/i/item/9789240029200 |
| *NeuroKit2* | Makowski et al. (2021). https://doi.org/10.3758/s13428-020-01516-y |
| *High-performance medicine* | Topol, E. (2019). *Nature Medicine*, 25, 44–56. |
| *Large language models encode clinical knowledge* | Singhal et al. (2023). *Nature*, 620, 172–180. |

---

## ⚖️ Licencia

Este material es de uso **educativo y académico** dentro del programa de posgrado de la Corporación Académica Ciencias Básicas Biomédicas.

Los datasets utilizados son de acceso público bajo sus respectivas licencias:
- **Iris, Breast Cancer Wisconsin, Cleveland Heart Disease:** UCI Machine Learning Repository
- **Pima Indians Diabetes:** NIDDK / Kaggle
- **Secuencia BRCA1:** NCBI GenBank (NM_007294.4)

```
MIT License — libre para uso académico con atribución.
```

---

## 🤝 Contribuciones

¿Encontraste un error o tienes una mejora? Las contribuciones son bienvenidas:

1. Haz un **fork** del repositorio.
2. Crea una rama: `git checkout -b mejora/descripcion-breve`
3. Realiza tus cambios y haz commit: `git commit -m "Descripción del cambio"`
4. Abre un **Pull Request** con descripción clara del cambio propuesto.

---

## 📬 Contacto

**Corporación Académica Ciencias Básicas Biomédicas**  
Maestría y Doctorado en Ciencias Básicas Biomédicas  

> Para dudas sobre el contenido del módulo, comunícate a través de los canales oficiales del programa.

---

<div align="center">

*Desarrollado con 🧬 para la formación de investigadores en Ciencias Básicas Biomédicas*  
*Corporación Académica Ciencias Básicas Biomédicas · 2026*

</div>
