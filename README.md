# 📊 CallMeMaybe - Análisis de eficiencia de operadores

## 🎯 Descripción del proyecto

**CallMeMaybe** es un servicio de telefonía virtual que busca mejorar la calidad de su atención al cliente mediante la identificación de operadores con bajo desempeño.

El objetivo de este proyecto es analizar métricas operativas clave para detectar ineficiencias en el manejo de llamadas y apoyar la toma de decisiones basada en datos.

---

## 🧠 Objetivo del análisis

Identificar operadores menos eficaces a partir de:

* 📞 Alta tasa de llamadas perdidas
* ⏳ Tiempos de espera elevados
* 📉 Bajo volumen de llamadas atendidas

A través del análisis exploratorio y la creación de métricas, se detectan patrones de desempeño que permiten priorizar acciones correctivas.

---

## 📂 Dataset

**Fuente:** Dataset proporcionado para análisis interno del servicio CallMeMaybe.

### Archivos utilizados:

* `telecom_dataset_new.csv`
* `telecom_clients.csv`

---

## 📊 Descripción de los datos

El dataset contiene información detallada sobre la operación del servicio, incluyendo:

* Llamadas entrantes y salientes
* Operadores asignados
* Tiempos de espera
* Estado de las llamadas (atendida / perdida)

### Columnas principales:

* `operator_id` — Identificador del operador
* `call_id` — Identificador de la llamada
* `direction` — Dirección de la llamada (entrante/saliente)
* `is_missed_call` — Indicador de llamada perdida
* `call_duration` — Duración de la llamada
* `avg_wait_time` — Tiempo promedio de espera
* `total_in_calls` — Total de llamadas entrantes

---

## 🛠️ Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🚀 Enfoque del análisis

1. Exploración y limpieza de datos (EDA)
2. Creación de métricas por operador
3. Definición de criterios de ineficiencia (percentil 75)
4. Identificación de operadores críticos
5. Visualización de resultados para toma de decisiones

---

## 💼 Impacto del proyecto

Este análisis permite:

* Detectar operadores con bajo desempeño
* Optimizar la asignación de recursos
* Mejorar la experiencia del cliente
* Apoyar decisiones operativas basadas en datos

---

