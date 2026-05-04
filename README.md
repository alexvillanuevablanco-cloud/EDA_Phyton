# Proyecto EDA con Python - Campañas de marketing bancario

## Descripción del proyecto

En este proyecto se ha realizado un análisis exploratorio de datos (EDA) sobre dos datasets relacionados con campañas de marketing directo de una entidad bancaria portuguesa.

El objetivo principal ha sido entender mejor el comportamiento de los clientes y detectar qué variables parecen estar más relacionadas con la contratación de un depósito a plazo. 
Para ello, se ha trabajado con Python, utilizando principalmente `pandas` para la manipulación de datos y `matplotlib` para las visualizaciones.

Además del análisis, también se ha llevado a cabo una fase de limpieza, transformación y unión de los datasets, con el fin de trabajar sobre una base de datos más completa y consistente.

---

## Objetivos

Los objetivos de este proyecto han sido:

- Cargar y explorar los datasets proporcionados.
- Limpiar y transformar los datos para dejarlos listos para el análisis.
- Unir ambos conjuntos de datos mediante el identificador del cliente.
- Realizar un análisis descriptivo de las variables más relevantes.
- Crear visualizaciones que ayuden a interpretar mejor los datos.
- Extraer conclusiones útiles a partir de los resultados obtenidos.

---

## Datasets utilizados

### 1. `bank-additional.csv`
Dataset principal con información sobre:
- características del cliente
- información de contacto
- datos de la campaña de marketing
- resultado final de la suscripción (`y`)

### 2. `customer-details.xlsx`
Archivo Excel complementario con información adicional del cliente:
- ingresos
- número de hijos/adolescentes en el hogar
- fecha de alta como cliente
- visitas mensuales a la web

Este archivo contiene 3 hojas distintas, que fueron unificadas en un único dataframe antes de realizar el análisis.

---

## Tecnologías utilizadas

- Python
- Pandas
- Matplotlib
- Visual Studio Code
- Jupyter Notebook

---

## Estructura del proyecto

```bash
proyecto-eda-banco/
│
├── README.md
├── data/
│   ├── raw/
│   │   ├── bank-additional.csv
│   │   └── customer-details.xlsx
│   └── processed/
│       └── merged_data.csv
│
├── notebooks/
│   └── eda_banco.ipynb
│
└── src/
