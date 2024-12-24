# TFM: Aplicación de algoritmos adaptativos y detección del drift para la predicción del cierre del IBEX-35

Este repositorio contiene los notebooks, la memoria y recursos necesarios para el desarrollo de mi Trabajo de Fin de Máster (TFM). A continuación, se explican los pasos para configurar el entorno y ejecutar los notebooks.

## Instrucciones de uso

1. **Clonar el repositorio, configurar el entorno y ejecutar los notebooks**  
   - Descarga o clona este repositorio en tu máquina local:
     ```bash
     git clone https://github.com/tu-usuario/tu-repositorio.git
     ```
   - Si usas Anaconda, sigue estos pasos para configurar el entorno:
     - Importa el entorno desde el archivo `environment.yml` incluido en el repositorio:
       ```bash
       conda env create -f environment.yml
       ```
     - Activa el entorno:
       ```bash
       conda activate nombre-del-entorno
       ```
   - Abre los notebooks de **Preprocesamiento** y **EDA** dentro de Anaconda y ejecútalos en el entorno configurado.
   - Para ejecutar el notebook **Aprendizaje incremental**:
     - Este no debe ejecutarse dentro de Anaconda.
     - Usa un editor como **VSCode**.
     - Asegúrate de tener instalada la librería `river==0.21.2`:
       ```bash
       pip install river==0.21.2
       ```

## Notebooks incluidos
- **Preprocesamiento:** Limpieza y transformación de los datos.
- **EDA:** Visualización y análisis inicial de los datos.
- **Aprendizaje incremental:** Implementación y análisis de modelos incrementales.

---
