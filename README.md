# 📊 Análisis de Evasión de Clientes (Churn) - Telecom X

Este proyecto forma parte del desafío **Telecom X**, cuyo objetivo es analizar la pérdida de clientes (Churn) mediante técnicas de análisis de datos y visualización, utilizando Python en Google Colab.

---

## 📌 Objetivo

Identificar los principales factores que influyen en la cancelación del servicio por parte de los clientes y proporcionar recomendaciones estratégicas para mejorar la retención, basadas en datos.

---

## 🛠 Tecnologías utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Estructura del proyecto

- `TelecomX_Data.json`: Datos reales de clientes (simulados).
- `TelecomX_diccionario.md`: Diccionario de variables del dataset.
- `TelecomX_Notebook.ipynb`: Cuaderno de Google Colab con todo el análisis.
- `README.md`: Descripción del proyecto.

---

## 🧪 Pasos realizados

### 1. Importación y Limpieza de Datos
- Lectura de datos desde archivo JSON.
- Conversión de columnas a tipos adecuados.
- Eliminación de valores nulos y duplicados.
- Renombramiento de columnas.
- Estandarización de datos binarios (Sí/No → 1/0).

### 2. Transformaciones
- Creación de columna `Cuentas_Diarias` (gasto mensual / 30).
- Creación de columna `Servicios_Contratados` (conteo de servicios activos por cliente).

### 3. Análisis Exploratorio de Datos (EDA)
- Análisis de distribución de churn.
- Visualización por tipo de contrato, método de pago, antigüedad, cargos y más.
- Boxplots, histogramas, mapas de calor, etc.

### 4. Correlación entre variables
- Matriz de correlación con `Churn`.
- Análisis de relación entre cantidad de servicios y evasión.
- Relación entre `Cuentas_Diarias` y churn.

### 5. Conclusiones y Recomendaciones
- Identificación de patrones críticos de evasión.
- Estrategias prácticas para reducir cancelaciones.

---

## 📈 Principales Insights

- Clientes con contratos mensuales y menor antigüedad tienen mayor riesgo de evasión.
- Los cargos diarios altos aumentan la probabilidad de churn.
- Contratar más servicios reduce significativamente el abandono.

---

## 💡 Recomendaciones

- Incentivar contratos de largo plazo.
- Programas de retención para clientes nuevos.
- Promociones por contratación de múltiples servicios.
- Sistema de alertas tempranas basado en comportamiento financiero.

---

## ✅ Estado del proyecto

`✅ Finalizado` – análisis completo y listo para usar como base en futuros modelos predictivos.

---

## 📄 Licencia

Este proyecto es de uso académico y educativo. Puedes usarlo, adaptarlo o extenderlo libremente. Si lo haces, te agradecería que menciones la fuente o des un 🌟 al repositorio.

---

## 🤝 Contribuciones

Si deseas proponer mejoras o agregar modelado predictivo en futuros pasos, ¡eres bienvenido a contribuir con un pull request o abrir una issue!

