# 📡 Telecom X - Análisis de Evasión de Clientes

Este repositorio contiene el análisis exploratorio y estratégico sobre la deserción de clientes de **Telecom X**. El objetivo es identificar patrones de fuga y proponer acciones de retención.

## 🛠️ Requisitos y Dependencias

El proyecto está desarrollado en **Python 3.10+**. Las principales librerías utilizadas son:

*   **Pandas**: Procesamiento y limpieza de datos.
*   **NumPy**: Operaciones numéricas.
*   **Matplotlib & Seaborn**: Visualizaciones estáticas.
*   **Plotly**: Gráficos interactivos.

## 🚀 Instalación y Configuración

Si deseas ejecutar este proyecto localmente, sigue estos pasos:

1.  **Clonar el repositorio**:
    ```bash
    git clone https://github.com/tu-usuario/telecom-x-churn.git
    cd telecom-x-churn
    ```

2.  **Crear un entorno virtual**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    ```

3.  **Instalar dependencias**:
    ```bash
    pip install pandas numpy matplotlib seaborn plotly requests
    ```

## 💻 Cómo Ejecutar el Proyecto

1.  **En Google Colab**: Sube el archivo `.ipynb` a tu Drive y ábrelo con Colab. Asegúrate de ejecutar las celdas en orden secuencial para garantizar la carga de los datos.


## 📊 Estructura del Notebook

*   `Extracción`: Carga de datos JSON desde API externa.
*   `Transformación`: Normalización de diccionarios anidados y traducción al español.
*   `EDA`: Visualización de tasas de evasión por demografía y servicios.
*   `Informe Final`: Resumen ejecutivo y recomendaciones estratégicas.

## ⚠️ Posibles Problemas y Soluciones

| Problema | Solución |
| :--- | :--- |
| **Error de conexión al cargar el JSON** | Verifica tu conexión a internet. La URL de GitHub debe ser accesible (raw content). |
| **Gráficos de Plotly no cargan** | Asegúrate de tener una versión actualizada de `nbformat`. En Colab, a veces requiere refrescar la celda. |
| **Valores nulos en Cargos Totales** | El script gestiona esto automáticamente convirtiendo errores a `NaN` y luego imputando `0`. |

---
*Desarrollado para el análisis de retención de clientes de Telecom X.*
