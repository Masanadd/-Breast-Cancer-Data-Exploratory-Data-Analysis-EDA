[Images_readme/Breast_cancer_pink_.png](https://github.com/Masanadd/-Breast-Cancer-Data-Exploratory-Data-Analysis-EDA/blob/main/Images_readme/Breast_cancer_pink_.png)

# Breast-Cancer-Data-Exploratory-Data-Analysis-EDA-
# Análisis Exploratorio de Datos (EDA) sobre Cáncer de Mama

## Descripción

Este repositorio contiene el análisis exploratorio de datos (EDA) realizado sobre la base de datos **SEER Breast Cancer Data** del repositorio IEEE Dataport. Este estudio tiene como objetivo identificar tendencias, patrones y relaciones entre las variables que puedan ayudar a mejorar la detección temprana y las estrategias de tratamiento del cáncer de mama.

---

## Objetivo del Proyecto

Comprender los factores asociados al cáncer de mama y cómo estos afectan la supervivencia de las pacientes, mediante la formulación de hipótesis basadas en factores demográficos, clínicos y tumorales.

---

## Contenido del Repositorio

### Archivos Principales
- **`data/`**: Dataset alojados en archivo Excel y Documentación en archivo Word
- **`notebooks/`**: Notebooks de Jupyter con el análisis paso a paso.
- **`README.md`**: Este archivo, que describe el propósito y los pasos clave del proyecto.

---

## Estructura del Análisis

### 1. Exploración Inicial de los Datos
- Tipos de variables analizadas:
  - **Numéricas:** Edad, tamaño del tumor, número de ganglios examinados/positivos, supervivencia en meses.
  - **Categóricas:** Raza, estado civil, estadios TNM, grado del tumor, estatus hormonal (ER/PR), y estado actual (Alive/Dead).
- Identificación de valores faltantes y problemas de formato.

### 2. Metodología de Limpieza
- Ajuste y limpieza de nombres de variables.
- Conversión de valores incorrectos y eliminación de columnas irrelevantes.
- Reestructuración de datos para garantizar la coherencia.

### 3. Formulación de Hipótesis
- Hipótesis principales planteadas:
  1. El diagnóstico temprano mejora significativamente la supervivencia.
  2. Existen diferencias en la tasa de detección temprana por raza.
  3. La incidencia y supervivencia están influenciadas por factores demográficos.
  4. El tamaño del tumor es un predictor clave de la supervivencia.
  5. El estatus hormonal afecta la supervivencia y la mortalidad.
  6. Pacientes con cáncer metastásico inicial tienen menor supervivencia.
  7. La detección de ganglios positivos predice una mejor supervivencia.

### 4. Análisis de Supervivencia
- Curvas de Kaplan-Meier utilizadas para comparar:
  - Diagnóstico temprano vs tardío.
  - Tamaños de tumor.
  - Expresión de receptores hormonales (ER+/PR+).
  - Trajectorias de supervivencia por raza.
  - Localización del tumor (regional vs metastásico).

---

## Resultados Clave

### Conclusiones e Implicaciones Clínicas

| **Conclusión**                                    | **Implicación Clínica**                                       |
|---------------------------------------------------|--------------------------------------------------------------|
| **Disparidades raciales:** Reducirlas mejora la supervivencia. | Implementar acceso equitativo a diagnósticos y tratamientos.     |
| **Diagnóstico temprano:** Mejora resultados clínicos.          | Reforzar tamizaje y estrategias de detección temprana.        |
| **Tamaño del tumor:** Tumores pequeños tienen mejor pronóstico. | Identificar y tratar tumores en etapas iniciales.             |
| **Estatus hormonal:** Mejores opciones en perfiles favorables. | Personalizar tratamientos según perfil hormonal.              |
| **Localización del tumor:** Regionales tienen mejor pronóstico. | Detectar temprano para prevenir progresión a estadios avanzados. |
| **Ganglios afectados:** Relación directa con menor supervivencia. | Diagnosticar antes de que los ganglios sean afectados.        |
| **Diagnóstico temprano por raza:** No hay diferencias significativas. | Enfocar esfuerzos en mantener equidad en tasas de detección.  |

---

## Cómo Usar este Repositorio

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/Masanadd/Breast-Cancer-Data-Exploratory-Data-Analysis-EDA-.git
