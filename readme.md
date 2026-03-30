# 📊 Taller Módulo 1 — Salud Mundial

**Autor:** Norman Aya  
**Programa:** IA & Data Science — DevSeniorCode  
**Fecha de entrega:** Marzo 30 de 2026  

---

## 🧾 Descripción

Este proyecto tiene como objetivo analizar indicadores de salud a nivel mundial utilizando Python y la librería Pandas.  

A lo largo del desarrollo se trabajó en la exploración, limpieza y análisis de los datos, aplicando herramientas vistas durante el módulo como manejo de DataFrames, funciones como `groupby()` y cálculos estadísticos básicos.

---

## 🌍 Dataset

El archivo `salud_mundial.csv` contiene información de **159 países** con **13 variables** relacionadas con la salud:

| Columna | Descripción |
|---|---|
| `pais` | Nombre del país |
| `region` | Región geográfica |
| `nivel_ingresos` | Nivel económico |
| `esperanza_vida` | Años promedio de vida |
| `gasto_salud_usd` | Gasto en salud por persona |
| `mortalidad_infantil` | Muertes por cada 1000 nacidos |
| `medicos_por_1000` | Médicos por cada 1000 habitantes |
| `poblacion_urbana_pct` | % población urbana |
| `obesidad_pct` | % obesidad |
| `diabetes_pct` | % diabetes |
| `tabaquismo_pct` | % fumadores |
| `camas_hospital_por_1000` | Camas por cada 1000 hab. |
| `vacunacion_pct` | % cobertura de vacunación |

Durante el análisis se identificaron algunos valores nulos, los cuales fueron considerados en el proceso.

---

## ⚙️ Cómo ejecutar el proyecto

1. Descargar o clonar el repositorio:
   ```bash
   git clone <https://github.com/ayaraju24-rgb/Trabajo_modulo1_MasterIA.git>
   ```

2. Ingresar a la carpeta:
   ```bash
   cd Trabajo_modulo1
   ```

3. Instalar dependencias:
   ```bash
   pip install pandas jupyter matplotlib
   ```

4. Ejecutar el notebook:
   ```bash
   jupyter notebook taller_modulo1.ipynb
   ```

---

## 📊 Hallazgos y conclusiones

- **Hallazgo 1:** Europa presenta la mayor esperanza de vida promedio, mientras que África tiene los valores más bajos, evidenciando diferencias importantes entre regiones.

- **Hallazgo 2:** Se observa una relación entre el porcentaje de vacunación y la esperanza de vida, donde regiones con mayor cobertura presentan mejores resultados.

- **Hallazgo 3:** Variables como el nivel de ingresos y el acceso a servicios de salud influyen directamente en los indicadores analizados.

---

## 📈 Visualización

Se realizó una gráfica de barras para representar la esperanza de vida promedio por región, lo que permite comparar fácilmente las diferencias entre ellas.

---

## 🛠️ Tecnologías utilizadas

- Python 🐍  
- Pandas 📊  
- Matplotlib 📈  
- Jupyter Notebook 📓  
- Git & GitHub  

---

## 💬 Comentario final

Este trabajo permitió reforzar el uso de herramientas básicas de análisis de datos en Python.  

Aunque al inicio hubo algunas dificultades, especialmente en el manejo de funciones y agrupaciones, el proceso ayudó a comprender mejor cómo trabajar con datos reales y obtener conclusiones a partir de ellos.
