# 🧪Análisis A/B para Tienda Online

Este proyecto analiza una serie de hipótesis planteadas por el equipo de marketing de una tienda online, con el objetivo de aumentar los ingresos y mejorar la experiencia del usuario. Se utiliza un enfoque basado en frameworks de priorización y pruebas A/B para tomar decisiones informadas.

---

## ✅ Objetivos

- Priorizar hipótesis usando los frameworks **ICE** y **RICE**.
- Analizar resultados de un test A/B entre dos grupos (A y B).
- Evaluar métricas clave como ingresos, tasa de conversión y tamaño promedio de pedidos.
- Identificar valores atípicos que puedan sesgar el análisis.
- Determinar la significancia estadística de los resultados y formular recomendaciones.

---

## 🧰 Herramientas y Tecnologías

- **Python 3**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **SciPy**
- **Jupyter Notebook**

---

## 🔎 Estructura del Análisis

### Parte 1: Priorización de Hipótesis

- Carga y limpieza del archivo `hypotheses_us.csv`.
- Aplicación de frameworks **ICE** y **RICE** para calcular la prioridad.
- Comparación entre ambos métodos y análisis de resultados.

### Parte 2: Análisis del Test A/B

- Carga y limpieza de los datasets `orders_us.csv` y `visits_us.csv`.
- Eliminación de usuarios duplicados entre grupos A y B.
- Cálculo y visualización de:
  - Ingreso acumulado
  - Tamaño promedio de pedidos
  - Tasa de conversión diaria
- Identificación de valores atípicos mediante percentiles.
- Aplicación de la prueba **Mann-Whitney U** para evaluar significancia estadística.

---

## 📌 Resultados Clave

- El método **RICE** priorizó hipótesis con mayor alcance (reach), como agregar formularios de suscripción.
- El test A/B no mostró diferencias estadísticamente significativas en tamaño de pedido ni en tasa de conversión (aunque esta última estuvo cerca del umbral).
- Se identificaron valores atípicos en pedidos y usuarios que fueron excluidos para mayor precisión.

---

## 🧠 Recomendaciones

- Considerar al **Grupo B** como referencia si el objetivo es mejorar ligeramente la conversión.
- Validar con más datos si el formulario de suscripción tiene impacto positivo.
- Implementar una nueva prueba A/B con mayor tamaño muestral.
- Evaluar nuevas estrategias para aumentar el **tamaño promedio de pedido**.

---

## ▶️ Cómo Ejecutar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/reyesleo22/proyectos-portafolio.git
