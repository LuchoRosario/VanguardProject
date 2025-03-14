
## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes a través de diferentes etapas de un proceso. Se han utilizado múltiples fuentes de datos y técnicas de limpieza y transformación para obtener un conjunto de datos final que permita realizar análisis detallados y pruebas de hipótesis.

## Contenido del Proyecto

1. **Limpieza y Transformación de Datos**
    - Conversión de tipos de datos.
    - Unión de múltiples DataFrames.
    - Filtrado de clientes menores de 18 años.
    - Definición de grupos de edad y antigüedad.
    - Reemplazo de valores nulos y atípicos.

2. **Análisis Demográfico**
    - Agrupación de clientes por edad y antigüedad.
    - Cálculo del balance promedio por grupo.
    - Análisis de la distribución de género.

3. **Análisis del Proceso de Compleción**
    - Conversión de pasos del proceso a valores numéricos.
    - Identificación de clientes que completaron el proceso.
    - Análisis de la tasa de compleción por variación (Test vs Control).
    - Pruebas de hipótesis para comparar tasas de compleción.

4. **Análisis del Tiempo en Cada Paso**
    - Cálculo de la diferencia de tiempo entre pasos consecutivos.
    - Filtrado de valores atípicos.
    - Análisis del tiempo promedio por paso y variación.
    - Pruebas de hipótesis para comparar tiempos entre grupos.

5. **Análisis de Tasa de Error**
    - Identificación de errores en el proceso (pasos hacia atrás).
    - Cálculo de la tasa de error por variación.
    - Análisis de la distribución de errores.

## Resultados Clave

- **Tasa de Compleción**: El grupo de prueba (Test) mostró una tasa de compleción significativamente mayor en comparación con el grupo de control (Control).
- **Tiempo en Cada Paso**: Se observó una diferencia significativa en el tiempo promedio que toma completar cada paso entre los grupos Test y Control.
- **Tasa de Error**: La tasa de error fue mayor en el grupo de prueba (Test) en comparación con el grupo de control (Control).

## Requisitos

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Cómo Ejecutar el Proyecto

1. Clonar el repositorio:
    ```bash
    git clone https://github.com/tu_usuario/tu_repositorio.git
    cd tu_repositorio
    ```

2. Instalar las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

3. Ejecutar el Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Abrir y ejecutar las celdas del archivo `analisis_clientes.ipynb`.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para discutir cualquier cambio que desees realizar.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para obtener más detalles.

## Contacto

Para cualquier consulta, puedes contactarme a través de [lucianocroci2016@gmail.com](mailto:tu_email@dominio.com).