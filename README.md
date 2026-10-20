# SentinelML

**Detección de anomalías industriales y mantenimiento predictivo mediante aprendizaje automático**

SentinelML es un proyecto de aprendizaje automático (_Machine Learning_) enfocado en la detección de anomalías industriales y el mantenimiento predictivo. Su objetivo es explorar cómo el análisis de datos y los modelos de aprendizaje automático pueden ayudar a identificar comportamientos inusuales en máquinas y anticipar posibles fallas.

El proyecto se desarrolla de forma progresiva, comenzando con el análisis exploratorio de datos y avanzando hacia técnicas de aprendizaje automático y aprendizaje profundo (_Deep Learning_).

## 🎯 Objetivos

- Explorar y analizar datos de sensores industriales.
- Identificar patrones y relaciones entre las condiciones de funcionamiento de las máquinas y sus fallas.
- Implementar técnicas estadísticas para la detección de anomalías.
- Entrenar y evaluar modelos de aprendizaje automático.
- Experimentar con redes neuronales utilizando PyTorch.
- Desarrollar un flujo de trabajo reproducible y mantenible para proyectos de ciencia de datos e inteligencia artificial.

## 📊 Conjunto de datos

El conjunto de datos inicial es **AI4I 2020 Predictive Maintenance Dataset**, que contiene datos industriales sintéticos diseñados para simular escenarios de mantenimiento predictivo.

Incluye variables como:

- Temperatura del aire.
- Temperatura del proceso.
- Velocidad de rotación.
- Torque.
- Desgaste de la herramienta.
- Indicadores de fallas de las máquinas.

**Fuente:** [AI4I 2020 Predictive Maintenance Dataset — UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset)

Este conjunto de datos se utilizará para estudiar el comportamiento de las máquinas, investigar patrones asociados a las fallas y desarrollar modelos predictivos.

> **Nota:** Los datos son sintéticos y no representan mediciones reales de equipos industriales en producción.

## 🛠️ Tecnologías y herramientas

- **Lenguaje:** Python 3.12.
- **Análisis de datos:** NumPy y Pandas.
- **Visualización:** Matplotlib.
- **Aprendizaje automático:** Scikit-learn.
- **Aprendizaje profundo:** PyTorch.
- **Aceleración por GPU:** DirectML para operaciones compatibles con GPU AMD.
- **Entorno de desarrollo:** Visual Studio Code y notebooks de Jupyter.
- **Control de versiones:** Git y GitHub.

## 📁 Estructura del proyecto

```text
sentinelml/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
├── tests/
├── .gitignore
├── requirements.txt
└── README.md
```

- `data/raw/`: conjuntos de datos originales.
- `data/processed/`: datos limpios y transformados.
- `notebooks/`: análisis exploratorios y experimentos.
- `src/`: módulos y funcionalidades reutilizables en Python.
- `tests/`: pruebas automatizadas.

La estructura se irá ampliando a medida que avance el desarrollo del proyecto.

## 🚀 Instalación y ejecución

### Requisitos previos

- Python 3.12.
- Git.
- Visual Studio Code (recomendado).

### 1. Clonar el repositorio

```bash
git clone https://github.com/EzequielMartin/sentinelml.git
cd sentinelml
```

### 2. Crear el entorno virtual

```bash
python -m venv .venv
```

En Windows, utilizando Git Bash, activalo con:

```bash
source .venv/Scripts/activate
```

### 3. Instalar las dependencias

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

### 4. Ejecutar los notebooks

Abrí el proyecto en Visual Studio Code, seleccioná el intérprete de Python del entorno `.venv` y elegí ese mismo entorno como kernel al abrir un notebook de Jupyter.

> La aceleración por GPU mediante DirectML es opcional y requiere una combinación compatible de versiones de PyTorch, DirectML y los controladores del sistema.

## 🗺️ Hoja de ruta

- [ ] **Etapa 1 — Análisis exploratorio de datos:** comprender las variables, estudiar sus distribuciones y visualizar relaciones entre ellas.
- [ ] **Etapa 2 — Preparación de los datos:** revisar su calidad, preparar las características y establecer un proceso reproducible de preprocesamiento.
- [ ] **Etapa 3 — Detección estadística de anomalías:** implementar métodos de referencia e identificar observaciones inusuales.
- [ ] **Etapa 4 — Aprendizaje automático:** entrenar y comparar modelos para detectar anomalías y predecir fallas.
- [ ] **Etapa 5 — Aprendizaje profundo:** experimentar con redes neuronales y autoencoders utilizando PyTorch.
- [ ] **Etapa 6 — Evaluación de modelos:** comparar resultados y estudiar falsos positivos, falsos negativos y capacidad de generalización.
- [ ] **Etapa 7 — Despliegue:** explorar la exposición de los modelos mediante una API y la creación de un panel de monitoreo.

La hoja de ruta podrá modificarse a medida que evolucione el proyecto y se incorporen nuevos conocimientos y técnicas.

## 📈 Estado del proyecto

**Estado actual:** configuración inicial del entorno y preparación del proyecto.

En esta etapa se está organizando el entorno de desarrollo, preparando el conjunto de datos y estableciendo las bases para comenzar el análisis exploratorio.

## 📄 Licencia

La licencia del código y las condiciones de uso del conjunto de datos deben evaluarse por separado antes de redistribuirlos. Se respetarán las condiciones de licencia y atribución correspondientes a los datos utilizados.

---

Proyecto personal de aprendizaje práctico en análisis de datos, aprendizaje automático y aprendizaje profundo.
