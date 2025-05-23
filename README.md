# Proyecto Integrador Etapa I.
## Taller de Fortalecimiento al Egreso II.
### Retail Insights: Limpieza de datos y preparación para análisis.

---

Este repositorio contiene el desarrollo completo de la **Etapa I del Proyecto Integrador** correspondiente a la asignatura *Taller de Fortalecimiento al Egreso II* de la carrera de Ingeniería en Ciencia de Datos. En esta primera etapa se abordan las tareas de **identificación, revisión, limpieza y transformación de datos**, siguiendo buenas prácticas de preparación de datos para análisis exploratorio y minería.

---

## Estructura del repositorio

````
.
├── README.md
├── .gitignore
├── requirements.txt
├── data
│   ├── raw
│   │   └── data.csv                # Archivo original sin modificar
│   └── cleaned
│       └── data_cleaned.csv       # Versión limpia y transformada
├── notebooks
│   └── data_cleaning.ipynb        # Notebook con el proceso completo de limpieza
````

---

## Descripción del dataset

Siguiendo la sugerencia de las instrucciones del proyecto, se seleccionó un conjunto de datos público proveniente de la plataforma [Kaggle](https://www.kaggle.com/datasets), específicamente el dataset titulado **"Retail Insights: A Comprehensive Sales Dataset"**. Este archivo simula operaciones comerciales en un entorno minorista, incluyendo información sobre productos, clientes, descuentos, costos, márgenes y logística de entrega.

El dataset cuenta con 5,000 registros y 24 atributos. Está organizado en un archivo único en formato CSV.

---

## Objetivo del notebook

El notebook `data_cleaning.ipynb` contiene el proceso detallado de "higienización" del dataset. Incluye:

- Diagnóstico inicial (valores nulos, formatos, duplicados).
- Conversión de columnas monetarias y porcentajes.
- Conversión de fechas a formato `datetime`.
- Imputación y tipificación de datos faltantes.
- Eliminación de registros incompletos.
- Exportación del dataset limpio.

---

## Finalidad académica y profesional

Este repositorio fue creado como parte de un proyecto académico, pero también forma parte de mi portafolio como estudiante de Ingeniería en Ciencia de Datos. La estructura, el control de versiones y la claridad en la documentación buscan reflejar buenas prácticas aplicadas en entornos reales.

---

### Requisitos del entorno

Este proyecto fue desarrollado y probado con:

- Python 3.10
- pandas 1.3 o superior
- Jupyter Notebook 6.4 o superior

Puedes instalar las dependencias ejecutando:

```bash
pip install -r requirements.txt
```

---

## 🔗 Licencia y uso

Este repositorio fue desarrollado exclusivamente con fines educativos. El dataset es de uso libre y está disponible públicamente en Kaggle. No se utiliza información sensible ni datos reales de clientes o empresas.

---
